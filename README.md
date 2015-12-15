Simple javascript functions for broswer cookies usage

## setCookie(cookieName, cookieValue, expireDays,isGlobal)

Sets cookie in users browser

To create global cookie `Visited` with value `1`, which lasts for 3days and is accessible from any page in domain use

```javascript
setCookie('visited', 1, 3,true)
```

If you want that cookie would be accessible only from current page

```javascript
setCookie('visited', 1, 3,false)
```

## getCookie(cookieName)

Retrieves your cookie

```javascript
getCookie('visited') // => 1
```

## checkCookie(cookieName)

Checks if cookie exists

```javascript
checkCookie('visited') // => true
```

