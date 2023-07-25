# Sigstore for PDF

## Dependencies

Python: v3.10

Poetry: 1.5.1

## Actions

Install: `poetry install`

Sign: `poetry run sigstore sign pnas.1005766107.pdf`

Verify: `poetry run sigstore verify identity --cert-identity alessio.cimarelli@sparkfabrik.com --cert-oidc-issuer https://accounts.google.com pnas.1005766107.pdf`
