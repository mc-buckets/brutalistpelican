title: A post with code blocks
date: 2018-08-21
description: This a simple post that shows how code blocks will appear. Code blocks word wrap at smaller breakpoints. Syntax highlighting is supported via Pygments. Happy coding!
tags: code, syntax, python 

## Python Code block

```python
def my_handler(event, context):
	print("Received event: " + json.dumps(event, indent=2))
	handle(event['message'])
```

## JSON code block

```json
{
	"update_id": 8888,
	"message": {
	"chat": {
		"first_name": "Matt",
		"id": put_your_id_here,
		"last_name": "McManus",
		"type": "private",
		"rolename": "mcman_s"
	},
	"date": 1453851465,
	"from": {
		"first_name": "Matt",
		"id": put_your_id_here,
		"last_name": "McManus",
		"rolename": "mcman_s"
	},
	"message_id": 2,
	"text": "/start"
	}
}
```
