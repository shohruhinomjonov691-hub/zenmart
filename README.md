# Zenmart · Storefront Interface

A static online-store interface focused on product presentation, retail navigation, and catalog layout. Zenmart demonstrates frontend layout work using HTML and CSS, with a small JavaScript integration for product carousels.

## Included pages

| Page | Content |
| --- | --- |
| [`index.html`](index.html) | Storefront with category navigation, promotional sections, product collections, and carousels |
| [`product/all.html`](product/all.html) | Product catalog with category/filter presentation and product cards |

Shared navigation, search presentation, account/cart links, and footer sections give the two implemented pages a consistent retail interface.

## Technology

- HTML and CSS for page structure and styling.
- Swiper 11, loaded from a CDN, for storefront carousels.
- Google Fonts (Jost) and Font Awesome assets loaded externally.
- Local product, category, and promotional imagery.

## Run locally

No package installation or build step is required. Serve the repository root with any static web server. For example, with Python installed:

```bash
git clone --branch master https://github.com/shohruhinomjonov691-hub/zenmart.git
cd zenmart
python3 -m http.server 8080
```

Open `http://localhost:8080` for the storefront and `http://localhost:8080/product/all.html` for the catalog. Internet access is needed for the CDN scripts, fonts, and icons.

## Structure

```text
index.html                  Storefront
product/all.html            Product catalog
public/css/command.css      Shared styles
public/css/home.css         Storefront styles
public/css/product_all.css  Catalog styles
public/images/              Images and icons
```

## Project scope

The completed deliverable is the storefront and catalog interface. Product data is authored directly in HTML. Search/filter controls and account/cart links are interface elements; this repository does not implement a backend, authentication, checkout, or payment processing.

Additional files under `order/`, `other/`, `mypage/`, and `product/chosenProduct.html` are empty placeholders. Use the two implemented pages above when reviewing this project.

## Author

[Shokhrukhbek Inomjonov](https://github.com/shohruhinomjonov691-hub)
