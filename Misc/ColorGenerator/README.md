# ColorGenerator
Generate a random dark or light color or even both.
> **Details:**\
  **`CAR?: false`**\
  **`type: Snippet`**

**Code**
```js
// Light
{set;color;{randstr;abcdef;6}}
// Dark
{set;color;{randstr;0123456;6}}
// Complete Randomness
{set;color;{randstr;abcdef0123456;6}}
```

**Use**
```js
{channel.send;{a!ae;
  --title="{get;color}";
  --color="#{get;color}"
}}
```
