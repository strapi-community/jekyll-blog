# Jekyll blog with Strapi

Simple Jekyll blog powered by Strapi

### Backend

This Jekyll application use the Strapi blog template.
Create a Strapi project named `backend` using the [blog template](https://github.com/strapi/strapi-template-blog):

```
# Using Yarn
yarn create strapi-app backend --template https://github.com/strapi/strapi-template-blog

# Or using NPM
npx create-strapi-app backend --template https://github.com/strapi/strapi-template-blog
```

The Strapi server will automatically start and import sample seed data.

### Frontend

Leave the Strapi backend running in the background. Open another terminal tab, clone this repository and make sure you're in the `frontend` directory:

```bash
cd frontend
```

Install gems and start the Jekyll server:

```bash
bundle install
bundle exec jekyll serve
```

The Jekyll server will run here => [http://localhost:4000](http://localhost:4000)
