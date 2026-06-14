# A Small Surprise for My Girlfriend

The parts that may need modification are some sections of `index.html`.

It was discovered that setting the date to the "I love you" month may cause issues.

**A quick reminder to anyone forking this: this is not my original work.**

I found this on a front-end design website and thought it was interesting, so I copied the project into this repository. A roommate saw the page and used it, and his girlfriend liked it. Unexpectedly, she watched short videos and one showed someone coding at a computer with this page visible. Please do not claim this as your original work — it can cause trouble if discovered.

## Deployment (Vercel)

This is a static site and can be deployed to Vercel easily.

- Deploy with the Vercel CLI:

```bash
npm install -g vercel
vercel login
vercel        # follow the prompts to deploy (use --prod to deploy to production)
```

- Or connect this GitHub repository in the Vercel dashboard and enable automatic deployments from the `master` branch.

The repository includes a `vercel.json` that configures a static deployment serving `index.html` at the root.
