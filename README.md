# ESTOQUE.ai — Site

Interface web do sistema de estoque com leitor RFID (ESP32).

## Arquivos
- `index.html` — a aplicação completa (HTML, CSS e JavaScript em um único arquivo).
- `logo-mark.png` — logo usada como favicon e no cabeçalho.

## Como usar
Abra o `index.html` no navegador, ou hospede a pasta em qualquer servidor estático
(GitHub Pages, Netlify, etc.).

O app tenta se conectar ao ESP32 em `/api/estado`. Quando o leitor não está
disponível, mostra dados de exemplo para ilustrar o funcionamento.
