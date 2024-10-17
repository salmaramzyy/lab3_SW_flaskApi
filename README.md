{
	"info": {
		"_postman_id": "b88bad43-eb65-43bb-a18f-e7bbe3e4d835",
		"name": "MYCollection",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "39068302"
	},
	"item": [
		{
			"name": "http://127.0.0.1:3000/todos/",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "mysecrettoken",
							"type": "string"
						}
					]
				},
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://127.0.0.1:3000/todos/",
					"protocol": "http",
					"host": [
						"127",
						"0",
						"0",
						"1"
					],
					"port": "3000",
					"path": [
						"todos",
						""
					]
				}
			},
			"response": []
		},
		{
			"name": "http://127.0.0.1:3000/todos/",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "mysecrettoken",
							"type": "string"
						}
					]
				},
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "    {\r\n        \"completed\": true,\r\n        \"title\": \"task4\"\r\n    }",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://127.0.0.1:3000/todos/",
					"protocol": "http",
					"host": [
						"127",
						"0",
						"0",
						"1"
					],
					"port": "3000",
					"path": [
						"todos",
						""
					]
				}
			},
			"response": []
		},
		{
			"name": "http://127.0.0.1:3000/todos/",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "mysecrettoken",
							"type": "string"
						}
					]
				},
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "    {\r\n        \"completed\": true,\r\n        \"title\": \"task2\"\r\n    }",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://127.0.0.1:3000/todos/",
					"protocol": "http",
					"host": [
						"127",
						"0",
						"0",
						"1"
					],
					"port": "3000",
					"path": [
						"todos",
						""
					]
				}
			},
			"response": []
		},
		{
			"name": "http://127.0.0.1:3000/todos/",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "    {\r\n        \"completed\": false,\r\n        \"title\": \"task3\"\r\n    }",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://127.0.0.1:3000/todos/",
					"protocol": "http",
					"host": [
						"127",
						"0",
						"0",
						"1"
					],
					"port": "3000",
					"path": [
						"todos",
						""
					]
				}
			},
			"response": []
		},
		{
			"name": "http://127.0.0.1:3000/todos/",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "    {\r\n        \"completed\": true,\r\n        \"title\": \"task4\"\r\n    }",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://127.0.0.1:3000/todos/",
					"protocol": "http",
					"host": [
						"127",
						"0",
						"0",
						"1"
					],
					"port": "3000",
					"path": [
						"todos",
						""
					]
				}
			},
			"response": []
		},
		{
			"name": "http://127.0.0.1:3000/todos/1",
			"request": {
				"method": "PUT",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "    {\r\n        \"completed\": true,\r\n        \"title\": \"task1\"\r\n    }",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://127.0.0.1:3000/todos/1",
					"protocol": "http",
					"host": [
						"127",
						"0",
						"0",
						"1"
					],
					"port": "3000",
					"path": [
						"todos",
						"1"
					]
				}
			},
			"response": []
		},
		{
			"name": "http://127.0.0.1:3000/todos/",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "mysecrettoken",
							"type": "string"
						}
					]
				},
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://127.0.0.1:3000/todos/",
					"protocol": "http",
					"host": [
						"127",
						"0",
						"0",
						"1"
					],
					"port": "3000",
					"path": [
						"todos",
						""
					]
				}
			},
			"response": []
		},
		{
			"name": "http://127.0.0.1:3000/todos/4",
			"request": {
				"auth": {
					"type": "bearer",
					"bearer": [
						{
							"key": "token",
							"value": "mysecrettoken",
							"type": "string"
						}
					]
				},
				"method": "DELETE",
				"header": [],
				"url": {
					"raw": "http://127.0.0.1:3000/todos/4",
					"protocol": "http",
					"host": [
						"127",
						"0",
						"0",
						"1"
					],
					"port": "3000",
					"path": [
						"todos",
						"4"
					]
				}
			},
			"response": []
		}
	]
}
