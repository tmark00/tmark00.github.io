# tmark00.github.io

Domena aplikacji Tesla Fleet API dla prywatnej instalacji TWCManager.

- `/.well-known/appspecific/com.tesla.3p.public-key.pem` - klucz publiczny (secp256r1),
  którego Tesla wymaga przy rejestracji partnera. Musi tu zostać na stałe.
- `/tesla-callback/` - adres zwrotny OAuth; pokazuje pełny URL do skopiowania i wklejenia
  w TWCManagerze (tryb paste-back). Niczego nie wysyła.
- `.nojekyll` - bez tego GitHub Pages pomija katalogi zaczynające się od kropki.
