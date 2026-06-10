# Deep-Sea Metals Dashboard

Tableau de bord sobre pour suivre les cours des métaux liés aux ressources des fonds marins.

## Métaux suivis
- Cuivre (COMEX:HG1!)
- Nickel (LME:NI1!)
- Cobalt (LME:CO1!)
- Zinc (LME:ZN1!)
- Or (COMEX:GC1!)
- Manganèse (TVC:MANGANESE)
- Lithium (TVC:LITHIUM)

## Déploiement sur Vercel (5 minutes)

### Option 1 — Via GitHub (recommandé)
1. Crée un repo GitHub et push ce dossier
2. Va sur vercel.com → "Add New Project"
3. Importe ton repo GitHub
4. Laisse tous les paramètres par défaut (Next.js détecté automatiquement)
5. Clique "Deploy" → c'est en ligne

### Option 2 — Via Vercel CLI
```bash
npm i -g vercel
vercel login
vercel --prod
```

## Développement local
```bash
npm install
npm run dev
# → http://localhost:3000
```

## Remarque sur les terres rares
Les REY ne sont pas cotées sur des marchés organisés.
Sources alternatives : asianmetal.com / usgs.gov
