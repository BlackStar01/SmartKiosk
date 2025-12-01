# SmartKiosk – Borne interactive + App mobile compagnon en .NET MAUI

**Une seule app · Un seul code source · Deux expériences totalement différentes**  
iOS • Android • Windows • Mac Catalyst

→ Sur tablette ou grand écran tactile → **mode borne interactive** (plein écran, gestes, navigation ultra-simplifiée)  
→ Sur smartphone → **mode application compagnon** (personnalisée, notifications, historique)

## Le concept qui fait craquer tous les clients retail, immobilier, culture & événementiel

| Secteur                  | Usage concret en 2025-2026                                      | Ce que SmartKiosk remplace aujourd’hui                  |
|--------------------------|------------------------------------------------------------------|----------------------------------------------------------|
| Agences immobilières     | Tablette en vitrine + app client qui reçoit les fiches biens   | Site web mal adapté mobile + flyers papier               |
| Salons de coiffure / beauté | Borne pour prendre RDV + app qui rappelle 30 min avant        | Cahier papier + Google Calendar mal synchronisé          |
| Musées & expositions     | Borne interactive + audioguide sur le téléphone du visiteur    | Audioguides propriétaires hors de prix                  |
| Concessions auto / retail| Écran géant pour configurer un produit + app qui garde la config | Configurateur web lent + commerciaux qui perdent tout   |
| Hôtels & restaurants     | Borne de commande / check-in + app fidélité                     | Bornes propriétaires à 15-30 k€ pièce                    |

## Fonctionnalités principales

| Fonctionnalité                                   | Mode Mobile (smartphone)                  | Mode Kiosk (tablette / grand écran tactile)      |
|--------------------------------------------------|-------------------------------------------|--------------------------------------------------|
| Détection automatique du format d’appareil       | UI classique téléphone                    | Plein écran · gros boutons · gestures            |
| Navigation simplifiée (max 4 actions visibles)   | Non                                       | Toujours présente en bas ou sur les côtés        |
| Prise de RDV / réservation                       | Calendrier + confirmation push            | Sélection créneau + QR code généré instantanément|
| Génération QR code billet / fiche produit        | Reçu dans l’historique                    | Affiché en grand + envoi mail/SMS                |
| Catalogue produits ou biens immobiliers          | Liste filtrable                           | Carrousel géant + zoom photos plein écran        |
| Configurateur visuel (voiture, cuisine, etc.)    | Version légère                            | Version complète avec animations SkiaSharp       |
| Notifications push & rappels                     | 30 min avant RDV                          | Non applicable                                   |
| Synchronisation temps réel (SignalR)             | Historique personnel                      | Mise à jour instantanée de toutes les bornes     |
| Mode présentation automatique (diaporama)        | Non                                       | Démarre après 30 s d’inactivité                  |
| Statistiques d’usage & heatmaps des clics        | Non                                       | Dashboard manager accessible sur desktop         |
| Thème clair/sombre                               | Suivant le système                        | Forcé clair (meilleure lisibilité en magasin)    |
| Multilingue (FR / EN / ES)                       | Français                                  | Français                                 |

## Stack technique 100 % .NET 9 – 2025

- .NET MAUI 9.0  
- CommunityToolkit.Mvvm (MVVM)  
- Shell adaptatif (deux Shells chargés dynamiquement selon `DeviceInfo.Idiom`)  
- SkiaSharp + Lottie pour les animations fluides  
- Shiny.Net (notifications & background tasks)  
- Refit + SignalR pour la synchro temps réel  
- SQLite local (bornes hors-ligne possibles)  
- QrCode.Net pour génération QR  
- Polices Material Icons + NerdFonts

## Licence
MIT – Libre pour usage commercial et portfolio.

Prêt à remplacer tes bornes hors de prix par une solution 10× moins chère et 100× plus sexy ?  
Écris-moi.
