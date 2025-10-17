
# BeeBox — Dashboard de gestion de boxes de stockage

## Contexte de réalisation:
- Projet d'epreuve d'engagement étudiant (BTS SIO), 2025-2026
- L'epreuve d'engagement étudiant est une epreuve facultative du BTS SIO, elle permet de mettre en pratique les connaissances acquises en BTS SIO dans un projet réel
- Site fait bénévolement pour une agence de boxes de stockage

---

## Aperçu
BeeBox permet de **gérer la location de boxes** par un ou plusiers **agence** avec :
- Attribution d’un box à un locataire
- Gestion des locataires, agences, affectations, paiements, notes et calendrier d’occupation.
- KPI d’exploitation : taux d’occupation, rotations mensuelles, retards de loyer, etc.

---

## ✅ Fonctionnalités

| Domaine | Points clés |
| **Agences** | Création/édition d’agences, visibilité cloisonnée des données par agence (ownership). |
| **Boxes** | CRUD des boxes, statut (libre/occupé), notes, historique d’affectations. |
| **Locataires** | CRUD, multi‑location possible, coordonnées, validation basique (ex. téléphone FR 10 chiffres). |
| **Affectations** | Liaison box ↔ locataire avec dates de début/fin, bouton “libérer” pour clôture. |
| **Paiements** | Suivi des loyers, statut (OK / EN RETARD), base pour KPIs. |
| **Calendrier** | Vue calendrier d’occupation (saisonnalité). |
| **KPI** | Occupation par agence, boxes actifs par locataire, turnover, retards de loyer. |
| **Sécurité** | Sessions, rôles (Admin global vs Agents d’agence), requêtes préparées PDO. |

---

## 🔐 Sécurité & Rôles
- **Admin global** : voit et gère **toutes** les agences & données.
- **Agent d’agence** : accès **restreint** à son agence uniquement.

---

## 🖼️ Front‑office & Back‑office

- **Login** → redirection en fonction du rôle.
- **Admin** : dashboard complet, gestion agences/utilisateurs, KPI globaux.  
- **Agents** : gestion limitée à leur agence, affectations (nouvelle entrée, notes, libérer).

---

## 📄 Licence & Auteur
- **Licence** : projet privé, usage interne uniquement.  
- **Auteur/Produit** : BeeBox — ANDRE Antoine.  
- **Site web** : https://www.beeboxlaon.fr/
