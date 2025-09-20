# Registro de Viabilidade TEER Mitral (MitraClip / Pascal)

App estático otimizado para tablet, com PWA (offline), **logo Cardiodiagnóstico** no cabeçalho, rodapé e **marca d’água** no PDF (via impressão).

## Publicação (GitHub Pages)
1. Repositório (ex.: `teer-mitral-registro`) → subir todos os arquivos na raiz.
2. **Settings → Pages** → Deploy from a branch → `main` / (root).
3. Acesse: `https://<usuario>.github.io/<repo>/`. No iOS/Android → “Adicionar à Tela de Início”.

## Funcionalidades
- Classificação de viabilidade por critério (Ideal/Desafiador/Desaconselhável) com autoajustes por medidas.
- Exportar **JSON**, copiar **resumo**, **imprimir/Salvar em PDF** com **marca d’água** e logotipo no rodapé.
- PWA: funciona offline após o primeiro acesso.

## Limiar eco (resumo)
- **Coaptação**: CL ≥ 2 mm, CD ≤ 11 mm (ideal); 1–1,9 mm/11–13 mm (desafiador); fora (desaconselhável).
- **Flail**: gap ≤ 10 mm, largura ≤ 15 mm (ideal); 10–15/15–20 (desafiador); acima (desaconselhável).
- **Folheto útil**: ≥ 10 mm (ideal); 7–9 (desafiador); < 7 (desaconselhável).
- **MVA/Grad**: MVA ≥ 4,0 cm² e MG < 5 mmHg (ideal); 3,5–3,9 ou 5–7 (desafiador); fora (desaconselhável).

## Licença
MIT (ajuste conforme sua instituição).