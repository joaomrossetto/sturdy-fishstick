# sturdy-fishstick

 TikTok Recommender Extractor
Este projeto tem como objetivo automatizar a extração e organização de recomendações salvas no TikTok, como filmes, músicas, séries, games, restaurantes e receitas, a partir dos vídeos favoritos do usuário.

✨ Funcionalidades
📥 Importa links de vídeos salvos organizados por coleções no TikTok.
🧠 Analisa o conteúdo dos vídeos (via metadados, OCR e transcrição de áudio).
🗂️ Classifica automaticamente os vídeos por tipo de recomendação.
📄 Organiza os dados em uma planilha do Google Sheets, com abas separadas por categoria.
🔍 Extrai informações relevantes como nome, sinopse, ingredientes, endereço, etc.
🆓 Utiliza ferramentas gratuitas e open-source para análise de imagem, vídeo e texto.
🛠️ Tecnologias utilizadas
Python
Google Sheets API
Tesseract OCR
OpenAI Whisper (transcrição de áudio)
Hugging Face Transformers (classificação de texto)
TikTok Display API (para metadados dos vídeos)
🚀 Como usar
Extraia os links dos vídeos salvos no TikTok.
Organize os links em uma planilha do Google Sheets.
Execute o script para analisar os vídeos e preencher automaticamente a planilha com os dados extraídos.
