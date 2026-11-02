# 🥕 Quitoque Card — dépôt historique

> [!IMPORTANT]
> **Quitoque Card est désormais intégrée directement à l'intégration [Quitoque](https://github.com/AuroreVgn/quitoque), à partir de la version 1.5.0.**
> Ce dépôt séparé n'est plus destiné à recevoir de nouvelles versions de la carte. Il est conservé pour l'historique du projet, les anciennes versions et les captures d'écran.

## Installer la carte

Installez ou mettez à jour l'intégration **[AuroreVgn/quitoque](https://github.com/AuroreVgn/quitoque)** via HACS / Marketplace ou manuellement. Redémarrez Home Assistant.

La ressource JavaScript est fournie et enregistrée par l'intégration :

```text
/quitoque/quitoque-card.js
```

Ajoutez ensuite une carte manuelle :

```yaml
type: custom:quitoque-card
```

L'éditeur graphique, les modes détaillé/compact/planning et les actions sont conservés.

## Migration depuis l'installation séparée

1. Mettez à jour l'intégration Quitoque vers la version **1.5.0 ou supérieure**.
2. Vérifiez dans **Paramètres → Tableaux de bord → Ressources** que `/quitoque/quitoque-card.js` est présente.
3. Désinstallez l'ancienne carte `quitoque_card` installée séparément via HACS, si elle existe.
4. Supprimez uniquement son ancienne ressource JavaScript (par exemple `/hacsfiles/quitoque_card/quitoque-card.js` ou `/local/quitoque-card.js`), **pas** `/quitoque/quitoque-card.js`.
5. Actualisez le navigateur. Vos configurations de cartes `type: custom:quitoque-card` restent valides.

## Documentation et support

- [README complet, configuration et dépannage](https://github.com/AuroreVgn/quitoque#readme)
- [Signaler un problème](https://github.com/AuroreVgn/quitoque/issues)
- [Captures d'écran historiques](assets/)

Merci aux utilisateurs et contributeurs de la carte !
