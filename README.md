# Blog post illustrative apps

## N8N Automation ideas

Vote and get ideas about automations for your personal life or business.

## Set Your Development Goals

Customers and product owners often want all four from the following list of four qualities but you can pick only three. Or give up a little from all of them or any other combinations. That’s a fundamental law of any project (not just a software development project). Read more here: Agile Software Craftsmanship by Uncle Bob: https://medium.com/crewnew-com/agile-software-craftsmanship-by-uncle-bob-377882b3d8b

Live in server: https://calculate-development-goals.vercel.app/

## License

Feel free to use however you wish but keep the footer link. Used TailwindCSS [template from @bradtraversy](https://github.com/bradtraversy/tailwind-landing-page) that I built into [SvelteKit template and included DaisyUI](https://github.com/crewnew-git/sveltekit-template).

## TODO
Add possibility to lock values. Buut there must be easier way to do it than eg. adding to `reCalculateSpeed()` the below if statements and then to the other four functions, too.
```
speed + cost + done locked -> can't change anything
speed + cost locked -> change done
speed + done locked -> change cost
cost + done locked -> change speed
cost locked -> change speed & done
etc.
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
