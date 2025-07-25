# 🎧 Classificador de Subgênero Eletrônico

Projeto pessoal de Paulo Fontana para organizar playlists eletrônicas usando a API do Spotify e a OpenAI (GPT).

## 💡 Objetivo
Automatizar a classificação de faixas eletrônicas em subgêneros como:
- Brazilian Bass
- Slap House
- Electro House
- Techno
- Drum and Bass
- Outros

## ⚙️ Tecnologias Utilizadas
- Python
- [Spotipy](https://spotipy.readthedocs.io/) (API do Spotify)
- OpenAI API
- Pandas
- dotenv

## 🚀 Como usar

1. Crie um app no [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
2. Crie uma API Key da OpenAI
3. Crie um arquivo `.env` com:

```
SPOTIPY_CLIENT_ID=seu_id
SPOTIPY_CLIENT_SECRET=sua_secret
OPENAI_API_KEY=sua_openai_key
```

4. Crie um arquivo `minhas_faixas.csv` com a coluna `track_uri` contendo as URIs das faixas.

5. Execute o script principal:

```bash
python classificar_faixas.py
```

6. O resultado será salvo em `faixas_classificadas.csv` com o subgênero atribuído.

## 📄 Licença

Este projeto está licenciado sob a licença MIT.
