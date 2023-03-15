# Postman

<div align="center">
        <img src= "https://drive.google.com/uc?export=download&confirm=no_antivirus&id=1hdw3eZFGswGVgZX19krDZ-94tUowdJpT"  title="Postman" alt="Postman" width="60" height="60"/>
</div>

<h3 align="center"> HTTP status code </h3>

<details>
<summary>1xx</summary>

| 1xx | Informational       | информационные          |
| --- | ------------------- | ----------------------- |
| 100 | Continue            | продолжай               |
| 101 | Switching Protocols | переключение протоколов |
| 102 | Processing          | идёт обработка          |
| 103 | Early Hints         | ранняя метаинформация   |
</details>

<details>
<summary>2xx</summary>

| 2xx | Success                       | успешно                   |
| --- |------------------------------ | ------------------------- |
| 200 | OK                            | хорошо                    |
| 201 | Created                       | создано                   |
| 202 | Accepted                      | принято                   |
| 203 | Non-Authoritative Information | информация не авторитетна |
| 204 | No Content                    | нет содержимого           |
| 205 | Reset Content                 | сбросить содержимое       |
| 206 | Partial Content               | частичное содержимое      |
| 207 | Multi-Status                  | многостатусный            |
| 208 | Already Reported              | уже сообщалось            |
| 226 | IM Used                       | использовано IM           |

</details>

<details>
<summary>3xx</summary>

|  3xx |  Redirection       | перенаправление                                 |
| ---- |------------------- | ----------------------------------------------- |
|  300 |  Multiple Choices  | множество выборов                               |
|  301 |  Moved Permanently | перемещено навсегда                             |
|  302 |  Moved Temporarily | перемещено временно                             |
|  302 |  Found             | найдено                                         |
|  303 |  See Other         | смотреть другое                                 |
|  304 |  Not Modified      | не изменялось                                   |
|  305 |  Use Proxy         | использовать прокси                             |
|  306 |  зарезервировано   | код использовался только в ранних спецификациях |
|  307 | Temporary Redirect | временное перенаправление                       |
|  308 | Permanent Redirect | постоянное перенаправление                      |
</details>

<details>
<summary>4xx</summary>

| 4xx  |      Client Error                        |       ошибка клиента                   |
| ---- |----------------------------------------- | -------------------------------------- |
| 400  | Bad Request                              | неправильный, некорректный запрос      |
| 401  | Unauthorized                             | не авторизован, не представился        |
| 402  | Payment Required                         | необходима оплата                      |
| 403  | Forbidden                                | запрещено, не уполномочен              |
| 404  | Not Found                                | не найдено                             |
| 405  | Method Not Allowed                       | метод не поддерживается                |
| 406  | Not Acceptable                           | неприемлемо                            |
| 407  | Proxy Authentication Required            | необходима аутентификация прокси       |
| 408  | Request Timeout                          | истекло время ожидания                 |
| 409  | Conflict                                 | конфликт                               |
| 410  | Gone                                     | удалён                                 |
| 411  | Length Required                          | необходима длина                       |
| 412  | Precondition Failed                      | условие ложно                          |
| 413  | Payload Too Large                        | полезная нагрузка слишком велика       |
| 414  | URI Too Long                             | URI слишком длинный                    |
| 415  | Unsupported Media Type                   | неподдерживаемый тип данных            |
| 416  | Range Not Satisfiable                    | диапазон не достижим                   |
| 417  | Expectation Failed                       | ожидание не удалось                    |
| 418  | I’m a teapot                             | я — чайник                             |
| 419  | Authentication Timeout (not in RFC 2616) | обычно ошибка проверки CSRF            |
| 421  | Misdirected Request                      |                                        |
| 422  | Unprocessable Entity                     | необрабатываемый экземпляр             |
| 423  | Locked                                   | заблокировано                          |
| 424  | Failed Dependency                        | невыполненная зависимость              |
| 425  | Too Early                                | слишком рано                           |
| 426  | Upgrade Required                         | необходимо обновление                  |
| 428  | Precondition Required                    | необходимо предусловие                 |
| 429  | Too Many Requests                        | слишком много запросов                 |
| 431  | Request Header Fields Too Large          | поля заголовка запроса слишком большие |
| 449  | Retry With                               | повторить с                            |
| 451  | Unavailable For Legal Reasons            | недоступно по юридическим причинам     |
| 499  | Client Closed Request                    | клиент закрыл соединение               |
</details>

<details>
<summary>5xx</summary>

| 5xx | Server Error                    | ошибка сервера                         |
| --- |-------------------------------- | -------------------------------------- |
| 500 | Internal Server Error           | внутренняя ошибка сервера              |
| 501 | Not Implemented                 | не реализовано                         |
| 502 | Bad Gateway                     | плохой, ошибочный шлюз                 |
| 503 | Service Unavailable             | сервис недоступен                      |
| 504 | Gateway Timeout                 | шлюз не отвечает                       |
| 505 | HTTP Version Not Supported      | версия HTTP не поддерживается          |
| 506 | Variant Also Negotiates         | вариант тоже проводит согласование     |
| 507 | Insufficient Storage            | переполнение хранилища                 |
| 508 | Loop Detected                   | обнаружено бесконечное перенаправление |
| 509 | Bandwidth Limit Exceeded        | исчерпана пропускная ширина канала     |
| 510 | Not Extended                    | не расширено                           |
| 511 | Network Authentication Required | требуется сетевая аутентификация       |
| 520 | Unknown Error                   | неизвестная ошибка                     |
| 521 | Web Server Is Down              | веб-сервер не работает                 |
| 522 | Connection Timed Out            | соединение не отвечает                 |
| 523 | Origin Is Unreachable           | источник недоступен                    |
| 524 | A Timeout Occurred              | время ожидания истекло                 |
| 525 | SSL Handshake Failed            | квитирование SSL не удалось            |
| 526 | Invalid SSL Certificate         | недействительный сертификат SSL        |

</details>

---

|          |                                                                                                                                            |
| -------- |------------------------------------------------------------------------------------------------------------------------------------------- |
| GET      | запросы используются для получения данных с сервера, не меняют состояние данных на сервере (не добавляют, не удаляют и не изменяют данные) |
| POST     | запросы используются для отправки новых данных на сервер                                                                                   |
| PUT      | изменение существующего объекта                                                                                                            |
| PATCH    | обновить некоторые существующие поля данных                                                                                                |
| DELETE   | удалить существующие данные                                                                                                                |
| COPY     |            |
| HEAD     |            |
| OPTIONS  |            |
| LINK     |            |
| UNLINK   |            |
| PURGE    |            |
| LOCK     |            |
| UNLOCK   |            |
| PROPFIND |            |
| VIEW     |            |






---

<h1 align="center">
        This is my collection from Postman
</h1>

```
{
	"info": {
		"_postman_id": "abf08c40-a014-4a0c-b5c6-1ae07254edf5",
		"name": "first",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "22622826"
	},
	


	"item": [
		{
			"name": "/get_method",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						}
					]
				},
				
				"url": {
					"raw": "http://162.55.220.72:5005/get_method?name=katy&age=12",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"get_method"
					],
					"query": [
						{
							"key": "name",
							"value": "katy"
						},
						{
							"key": "age",
							"value": "12"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "/user_info_3",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "katy",
							"type": "text"
						},
						{
							"key": "age",
							"value": "12",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "2000",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/user_info_3?name=katy&age=12&salary=2000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"user_info_3"
					],
					"query": [
						{
							"key": "name",
							"value": "katy"
						},
						{
							"key": "age",
							"value": "12"
						},
						{
							"key": "salary",
							"value": "2000"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "/object_info_1",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_1?name=katy&age=12&weight=45",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"",
						"object_info_1"
					],
					"query": [
						{
							"key": "name",
							"value": "katy"
						},
						{
							"key": "age",
							"value": "12"
						},
						{
							"key": "weight",
							"value": "45"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "/object_info_2",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_2?name=katy&age=12&salary=2000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_2"
					],
					"query": [
						{
							"key": "name",
							"value": "katy"
						},
						{
							"key": "age",
							"value": "12"
						},
						{
							"key": "salary",
							"value": "2000"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "/object_info_3",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_3?name=katy&age=12&salary=2000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_3"
					],
					"query": [
						{
							"key": "name",
							"value": "katy"
						},
						{
							"key": "age",
							"value": "12"
						},
						{
							"key": "salary",
							"value": "2000"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "/object_info_4",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_4?name=katy&age=12&salary=2000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_4"
					],
					"query": [
						{
							"key": "name",
							"value": "katy"
						},
						{
							"key": "age",
							"value": "12"
						},
						{
							"key": "salary",
							"value": "2000"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "/user_info_2",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						},
						{
							"key": "",
							"value": "",
							"type": "text",
							"disabled": true
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_4?name=katy&age=12&salary=2000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_4"
					],
					"query": [
						{
							"key": "name",
							"value": "katy"
						},
						{
							"key": "age",
							"value": "12"
						},
						{
							"key": "salary",
							"value": "2000"
						}
					]
				}
			},
			"response": []
		}
	]
}
```
