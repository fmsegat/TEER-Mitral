# Registro de Viabilidade TEER Mitral (MitraClip / Pascal)

Aplicativo estático (HTML único) para registro estruturado de avaliação eco pré-TEER mitral (MitraClip/PASCAL), otimizado para tablet.

## Como publicar em GitHub Pages (Project Page)

1. Crie um repositório no GitHub, por exemplo: `teer-mitral-registro`.
2. Faça upload destes arquivos (ou use os comandos git abaixo).
3. Em **Settings › Pages**, em **Build and deployment**, selecione:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` e **/ (root)`
4. Acesse a URL: `https://<seu-usuario>.github.io/<nome-do-repo>/`.

## Git rápido

```bash
git init
git add .
git commit -m "Publica TEER Mitral registro"
git branch -M main
git remote add origin https://github.com/<seu-usuario>/<nome-do-repo>.git
git push -u origin main
```

## Estrutura

- `index.html` — aplicação única, sem dependências.
- `.nojekyll` — desativa o Jekyll no GitHub Pages para evitar interferências.
- `README.md` — este guia.

## Licença

MIT — adapte conforme sua preferência institucional.

## PWA (Offline no tablet/celular)

Este app já inclui **manifest.json** e **service-worker.js**. Depois de publicado no GitHub Pages:
- Acesse pelo Safari/Chrome no dispositivo e **Adicionar à Tela de Início**.
- O app abrirá em modo **standalone** e funcionará **offline** após o primeiro carregamento.

## Ícones/Favicon

Inclusos em `icons/` (192 e 512 px). Você pode substituir por arte do Cardiodiagnóstico (mesmo nome/paths).

## Limiares eco (resumo usado nos chips)

- **Coaptação**: CL ≥ 2 mm e CD ≤ 11 mm (ideal); 1–1,9 mm ou 11–13 mm (desafiador); fora disso (desaconselhável).  
- **Flail/Prolapso**: gap ≤ 10 mm e largura ≤ 15 mm (ideal); 10–15 mm/15–20 mm (desafiador); acima disso (desaconselhável).  
- **Comprimento útil de folheto**: ≥ 10 mm (ideal); 7–9 mm (desafiador); < 7 mm (desaconselhável).  
- **Área/Gradiente**: MVA ≥ 4,0 cm² e MG < 5 mmHg (ideal); 3,5–3,9 cm² ou 5–7 mmHg (desafiador); abaixo/acima disso (desaconselhável).  
- **Jets**: alvo central A2–P2 preferível; múltiplos não adjacentes/comissurais pioram a classificação.  
- **Calcificação/Cleft**: ausente (ideal); focal leve (desafiador); extensa/na linha de grasp (desaconselhável).  

> Estes limiares orientam a **sinalização**; decisão final depende do contexto clínico, experiência do time e avaliação multiparamétrica.

## Publicação rápida (GitHub Pages)

1. Repositório `teer-mitral-registro` → subir todos os arquivos na raiz.  
2. **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main` (root).  
3. A URL ficará: `https://<seu-usuario>.github.io/<repo>/`.

