
## Quick intro to this template

You can edit pages in [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). However, this theme ([material](https://squidfunk.github.io/mkdocs-material/)) has many fancy extensions, like [admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/):

!!! info "Using html snippets"
    If you want to add an image, the best way would be to use html, e.g:

    ```html
    <figure>
    <img src="https://elixir-europe.org/sites/default/files/ebif_news_release_image_news_landingpageimage_.png" width="600" alt="Image on elixir landing page"/>
    <figcaption> Elixir image </figcaption>
    </figure>
    ```
    
    Which would result in:

    <figure>
    <img src="https://elixir-europe.org/sites/default/files/ebif_news_release_image_news_landingpageimage_.png" width="600" alt="Image on elixir landing page"/>
    <figcaption> Elixir image </figcaption>
    </figure>

    If you want to use local images, add them to `docs/assets/images` and refer to them in the html as a relative path, e.g.:

    ```html
    <figure>
    <img src="../assets/images/elixir_image.png" width="600" alt="Image on elixir landing page"/>
    <figcaption> Elixir image </figcaption>
    </figure>
    ```

    Resulting in: 

    <figure>
    <img src="../assets/images/elixir_image.png" width="600" alt="Image on elixir landing page"/>
    <figcaption> Elixir image </figcaption>
    </figure>

By using the bibtex plugin, we can use citations. Add your references in `references.bib`, and cite [@hoebelheinrich_nancy_j_2022_6769695] like this:

```
[@firstauthor_2022]
```

\bibliography
