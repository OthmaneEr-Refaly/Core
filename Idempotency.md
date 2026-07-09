Your answer:

> no matter how many times you execute them, you achieve the same result

## Score

**9.5/10**

Excellent.

Only one thing.

You wrote

> "we can use it on GET PUT POST..."

Careful.

POST is **NOT idempotent**.

---

A quick table

|Method|Idempotent?|
|---|---|
|GET|✅|
|PUT|✅|
|DELETE|✅|
|POST|❌|
|PATCH|Usually ❌|

---

### Interview answer

> Idempotency means that performing the same operation multiple times has the same effect as performing it once. For example, calling PUT multiple times with the same data leaves the resource in the same state. POST is generally not idempotent because each request may create a new resource.

## Related - [[HTTP Methods]] - [[REST]]