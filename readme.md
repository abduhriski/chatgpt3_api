# ChatGPT3 API Wrapper

Repositori ini merupakan wrapper untuk mengakses API ChatGPT 3

## Catatan Instalasi

Library yang digunakan adalah `requests`

## Cara Menggunakan

```
from chatgpt3 import ChatGPT3

gpt3 = ChatGPT3("API Token OpenAI")
gpt3.chat("Nama kamu siapa ?")
```

### Bagaimana cara mendapatkan API Token dari OpenAI ?
- Buka website[OpenAI](https://beta.openai.com/).
- Login atau Daftar jika belum punya akun
- Klik menu `profile` di kanan atas
- Klik `View API keys`.
- Klik pada `Create new secret key`
- Catat token API anda
