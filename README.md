# Tesla Fleet API Public Key Hosting

This repository hosts the public key required for Tesla Fleet API registration.

## Purpose

Tesla Fleet API requires developers to host a public key at a specific well-known URL:
```
https://[domain]/.well-known/appspecific/com.tesla.3p.public-key.pem
```

This repository is set up to host that public key using GitHub Pages.

## Structure

- `.well-known/appspecific/com.tesla.3p.public-key.pem` - The public key file
- `index.html` - A simple landing page

## Usage

1. Fork or clone this repository
2. Replace the public key with your own
3. Enable GitHub Pages in the repository settings
4. Set up a custom domain (optional)
5. Verify the public key is accessible at the required URL
6. Complete the Tesla Fleet API registration process

## License

MIT
