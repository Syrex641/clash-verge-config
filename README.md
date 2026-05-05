# Clash Verge / Mihomo Cloud Config

This repository hosts a Clash Verge / Mihomo configuration template for use with Sub-Store.

## Files

- `config.template.yaml`: cloud-safe Clash/Mihomo template. It does not contain private subscription URLs.

## Usage With Sub-Store

1. Add your original proxy subscription in Sub-Store.
2. Create or edit a combined subscription.
3. In subscription editing, use the `代理/策略` section for the configuration template.
4. Point the template/profile URL to the GitHub raw URL for `config.template.yaml`.
5. Let Sub-Store output a Clash/Mihomo configuration subscription.
6. Import the Sub-Store output URL into Clash Verge.

Do not commit private airport subscription URLs or Sub-Store tokens to this repository.
