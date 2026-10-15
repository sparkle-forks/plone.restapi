`POST /@login` now returns the JWT as `access_token` instead of `token`. Volto stores `action.result.token`, so login appears to succeed while the session stays anonymous. @sparkle
