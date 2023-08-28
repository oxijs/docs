# Changelog for v2.3.0

## Fixes & improvements

> * **New functions + deprecations**
>
> ```diff
> + $createAdvancedObject[name;property]
> + $getAdvancedObject[objName;property?;format?]
> - $letJsonReq[url;name]
> - $getJsonReq[name;property?]
> ```
>
> * **Explanation**: `$letJsonReq` & `$getJsonReq` were quite basic functions, so now they have an "expanded" functionality, it's nearly the same thing, but you'll need to use `$jsonRequest[url;property?]` inside `$createAdvancedObject[name;object]` for making json requests.
> * Fixed AutoUpdate _(yup, again)_
