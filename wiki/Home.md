# Wirestack UI — Documentation

Wirestack UI est un système de composants Laravel/Livewire construit avec Tailwind CSS v4 et Alpine.js. Il fournit une bibliothèque de composants Blade prêts à l'emploi, des composants Livewire interactifs et un système de design tokens entièrement personnalisable.

---

## 🚀 Démarrage

| Page | Description |
| ---- | ----------- |
| [[Installation]] | Prérequis, installation via Composer, intégration des assets |
| [[Configuration]] | Référence complète du fichier `config/ws.php` |
| [[Directives-Blade]] | Directives `@wsStyles` et `@wsScripts` |

---

## 🎨 Design System

| Page | Description |
| ---- | ----------- |
| [[Design-Tokens]] | Variables CSS globales, palettes de couleurs |
| [[Themes-et-Mode-Sombre]] | Mode sombre, personnalisation avancée, animations |
| [[API-JavaScript]] | Helpers JS globaux : `DsToast`, `DsModal`, `DsDrawer`, etc. |

---

## 🧱 Composants Blade

### Atomes & Éléments de base

| Page | Composants |
| ---- | ---------- |
| [[Composants-Atomes]] | `Button`, `Badge`, `Avatar`, `AvatarGroup`, `Spinner`, `Icon`, `Divider`, `Kbd`, `Chip` |

### Formulaires

| Page | Composants |
| ---- | ---------- |
| [[Composants-Formulaires]] | `Input`, `Textarea`, `Select`, `Checkbox`, `Radio`, `Toggle`, `Range`, `FormGroup`, `FormSection`, `InputGroup` |

### Mise en page

| Page | Composants |
| ---- | ---------- |
| [[Composants-Mise-en-page]] | `Card`, `Container`, `Section`, `Stack`, `Inline`, `Panel` |

### Navigation

| Page | Composants |
| ---- | ---------- |
| [[Composants-Navigation]] | `Breadcrumb`, `Pagination`, `Steps`, `Nav`, `NavItem` |

### Affichage de données

| Page | Composants |
| ---- | ---------- |
| [[Composants-Affichage-de-donnees]] | `Stat`, `StatGroup`, `Table`, `Timeline`, `Code`, `CopyButton` |

### Feedback & États

| Page | Composants |
| ---- | ---------- |
| [[Composants-Feedback]] | `Alert`, `Progress`, `ProgressBar`, `Skeleton`, `EmptyState` |

### Interactifs

| Page | Composants |
| ---- | ---------- |
| [[Composants-Interactifs]] | `Dropdown`, `Tooltip`, `Popover`, `Tabs`, `Accordion`, `Collapsible` |

---

## ⚡ Composants Livewire

| Page | Description |
| ---- | ----------- |
| [[Livewire-Toast]] | Notifications non bloquantes (`DsToast`) |
| [[Livewire-Modal]] | Fenêtre modale (`DsModal`) |
| [[Livewire-Drawer]] | Panneau latéral (`DsDrawer`) |
| [[Livewire-DataTable]] | Tableau interactif avec recherche, tri, pagination |
| [[Livewire-Command-Palette]] | Palette de commandes ⌘K (`DsCommandPalette`) |

---

## Pré-requis

| Dépendance | Version minimum |
| ---------- | --------------- |
| PHP | 8.2 |
| Laravel | 11.0 ou 12.0 |
| Livewire | 4.0 |
| Tailwind CSS | v4 |
| Alpine.js | inclus avec Livewire 4 |
