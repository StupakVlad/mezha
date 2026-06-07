# mezha

Тут ви знайдете JSON для імпорту workflow, щоб можна було відкрити його та переглянути структуру. 
Роботу самого workflow можна побачити на робочому прикладі, про який я окремо розповім в інструкції.

Також на всяк випадок додаю тестовий приклад JSON. Він досить великий, оскільки саме в такому вигляді дані надходять на Webhook разом з інформацією про браузер та іншими службовими даними. 
У процесі роботи workflow ці дані будуть нормалізовані. Усе інше можна знайти в інструкції.

[
  {
    "headers": {
      "host": "n8n.thanksrobot.net",
      "x-real-ip": "141.101.105.24",
      "x-forwarded-for": "77.239.164.131, 141.101.105.24",
      "x-forwarded-proto": "https",
      "connection": "upgrade",
      "content-length": "544",
      "sec-fetch-dest": "empty",
      "referer": "http://178.104.36.67:8080/",
      "priority": "u=1, i",
      "accept-language": "en,pl;q=0.9,ru;q=0.8,en-US;q=0.7,uk;q=0.6",
      "cf-ray": "a0715df388ce5b67-VIE",
      "accept-encoding": "gzip, br",
      "sec-ch-ua-platform": "\"Windows\"",
      "user-agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/149.0.0.0 Safari/537.36",
      "sec-ch-ua": "\"Google Chrome\";v=\"149\", \"Chromium\";v=\"149\", \"Not)A;Brand\";v=\"24\"",
      "content-type": "application/json",
      "sec-ch-ua-mobile": "?0",
      "accept": "*/*",
      "origin": "http://178.104.36.67:8080",
      "sec-fetch-site": "cross-site",
      "sec-fetch-mode": "cors",
      "cdn-loop": "cloudflare; loops=1",
      "cf-connecting-ip": "77.239.164.131",
      "cf-ipcountry": "UA",
      "cf-visitor": "{\"scheme\":\"https\"}"
    },
    "params": {},
    "query": {},
    "body": {
      "name": "Влад Ступак",
      "company": "FOP",
      "email": "stupak.vlad@gmail.com",
      "phone": "+380954744869",
      "project_type": "web_app",
      "budget": "discuss",
      "timeline": "asap",
      "source": "tiktok",
      "message": "Хочу AI менеджера в Iнсту",
      "meta": {
        "submitted_at": "2026-06-05T18:51:09.052Z",
        "timezone": "Europe/Kiev",
        "locale": "en",
        "user_agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/149.0.0.0 Safari/537.36",
        "page_url": "http://178.104.36.67:8080/#services",
        "referrer": null,
        "viewport": "1933x879"
      }
    },
    "webhookUrl": "https://n8n.thanksrobot.net/webhook/3941ada5-e66a-496b-9b6c-df429c4260b2",
    "executionMode": "production"
  }
]
