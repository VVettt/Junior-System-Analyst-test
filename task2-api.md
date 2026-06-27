Задание 1.
```json
GET /api/v1/stores
Host: api.petrushka.ru
Authorization: Bearer {token}
```
   
Задание 2. 

```json
{
  "stores": [
    {
      "id": 1,
      "name": "METRO",
      "logo_url": "https://example.com/logos/metro.png",
      "delivery_type": "scheduled",
      "delivery_label": "Ближайшая доставка",
      "delivery_time": "сегодня 21:00-23:00",
      "external_url": "https://metro.ru"
    },
    {
      "id": 2,
      "name": "Ашан",
      "logo_url": "https://example.com/logos/auchan.png",
      "delivery_type": "scheduled",
      "delivery_label": "Ближайшая доставка",
      "delivery_time": "сегодня 18:00-20:00",
      "external_url": "https://auchan.ru"
    },
    {
      "id": 3,
      "name": "ВкусВилл",
      "logo_url": "https://example.com/logos/vkusvill.png",
      "delivery_type": "express",
      "delivery_label": "Быстрая доставка",
      "delivery_time": "от 20 до 60 минут",
      "external_url": "https://vkusvill.ru"
    },
    {
      "id": 4,
      "name": "ВИКТОРИЯ",
      "logo_url": "https://example.com/logos/viktoria.png",
      "delivery_type": "scheduled",
      "delivery_label": "Ближайшая доставка",
      "delivery_time": "сегодня 17:00-19:00",
      "external_url": "https://viktoria-group.ru"
    }
  ]
}
```
