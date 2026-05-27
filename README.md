# n8n-actus-bot
Workflow n8n automatisé : scraping quotidien d'actualités et envoi sur Discord via Webhook

# News Scraper — n8n + Discord

Workflow d'automatisation qui envoie chaque matin l'article 
"Fait du jour" du site Objectif Gard sur un channel Discord.

## Fonctionnement

Chaque jour à 10h, le workflow :
1. Récupère le HTML de la page d'accueil d'Objectif Gard
2. Parse le HTML en JavaScript pour extraire le lien de l'article "Fait du jour"
3. Envoie le lien automatiquement sur Discord via Webhook

## Stack

- n8n (workflow automation)
- Docker
- JavaScript
- Discord Webhook
