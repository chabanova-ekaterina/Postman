# Postman

<h1 align="center">
        This is my collection from Postman
</h1>

<!-- <div align="center">
        <img src= "https://drive.google.com/uc?export=download&confirm=no_antivirus&id=1hdw3eZFGswGVgZX19krDZ-94tUowdJpT"  title="Postman" alt="Postman" width="60" height="60"/>
</div>

<div id="header" align="center">
        <img src="https://drive.google.com/uc?export=download&confirm=no_antivirus&id=1rphVqbqgE0KxkkHsY5b8eNcsuRPGoUvv" />
        <img src="https://drive.google.com/uc?export=download&confirm=no_antivirus&id=1r9WPlBf3L-o6-ycB2Q2LrqXlf_2IkcN3" />
</div> -->


| 1xx  |     Informational   |       информационные      |
| ---- |-------------------- | ------------------------- |
|  100 |       Continue      |        продолжай        |
|  101 | Switching Protocols | переключение протоколов |
|  102 |     Processing      |     идёт обработка     |
|  103 |    Early Hints      | ранняя метаинформация  |


---

|  2xx |            Success            |           успешно         |
| ---- |------------------------------ | ------------------------- |
|  200 |               OK              |           хорошо          |
|  201 |            Created            |           создано         |
|  202 |            Accepted           |           принято         |
|  203 | Non-Authoritative Information | информация не авторитетна |
|  204 |           No Content          |       нет содержимого     |
|  205 |         Reset Content         |     сбросить содержимое   |
|  206 |        Partial Content        |    частичное содержимое   |
|  207 |          Multi-Status         |       многостатусный      |
|  208 |        Already Reported       |       уже сообщалось      |
|  226 |            IM Used            |       использовано IM     |

---

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

---

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

```
{
	"info": {
		"_postman_id": "abf08c40-a014-4a0c-b5c6-1ae07254edf5",
		"name": "first",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "22622826"
	},
	
```
```
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
