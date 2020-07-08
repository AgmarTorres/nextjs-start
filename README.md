This is a starter template for [Learn Next.js](https://nextjs.org/learn).

# Bibliotecas utilizadas

    npm install classnames
    npm install tailwindcss postcss-preset-env postcss-flexbugs-fixes
    npm install gray-matter

_app.js

    import '../styles/global.css'

    export default function App({ Component, pageProps }) {
        return <Component {...pageProps} />
    }


Recomendamos o uso de geração estática (com e sem dados) sempre que possível, porque sua página pode ser construída uma vez e veiculada pela CDN, o que torna muito mais rápido do que um servidor renderizar a página em todas as solicitações.

Você pode usar a geração estática para muitos tipos de páginas, incluindo:

Páginas de marketing
Postagens no blog
Listagens de produtos de comércio eletrônico
Ajuda e documentação

Isso é possível porque getStaticProps é executado apenas no lado do servidor .


# Server Side Props

    https://nextjs.org/docs/basic-features/data-fetching#getserversideprops-server-side-rendering

# Customizing PostCSS Config

    https://nextjs.org/docs/advanced-features/customizing-postcss-config

# Routing

    https://nextjs.org/docs/routing/introduction