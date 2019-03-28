# gatsby-theme-test
Testing how gatsby themes work

- Create packages.json
- Create packages and site folder
- Create `pacakges/gatsby-theme-test-blog` folder
- `yarn init` (gatsby-theme-test-blog)
- `yarn init` (site)
- `yarn workspace site add gatsby`
- `yarn workspace gatsby-theme-test-blog react react-dom -D`
- Add `gastsby-config.json`
- Create test `gatsby-theme-test-blog/src/pages/index.mdx` page
- `yarn workspace gatsby-theme-test-blog add gatsby-mdx`
- `yarn workspace gatsby-theme-test-blog add gatsby-plugin-page-creator`
- `yarn workspace gatsby-theme-test-blog add @mdx-js/mdx @mdx-js/tag`
- verify everything working with `yarn workspaces info`
