<h1 align="center">
  Create-Next-Diff
</h1>
<p align="center">Create-Next-Diff is a git diff collections that you can <strong>copy paste to build your full-stack Next.js apps</strong>. </p>

## Copy-Paste vs CLI vs Template
This project is heavily inspired by [shacd/ui](https://ui.shadcn.com/), [Kirimase](https://kirimase.dev/) and other Next.js template.

* shacd/ui is a "Beautifully designed components that you can copy and paste into your apps". It also has an [CLI tool](https://ui.shadcn.com/docs/cli) to add components to your project.
* "Kirimase is a command-line tool (CLI) for building full-stack Next.js apps faster. It supercharges your development workflow, allowing you to quickly integrate packages and scaffold resources for your application with best practices in mind.
* There are also tons of Next.js templates online.

Issues
* Configuring a particular tech(eg. Stripe) with a particular framework (eg. NextJs) could take hours.
* Template is magical but it contains too many technologies! Dev could spend hours understanding which codes are configuring which tech.
* Kirimase is great but I find myself creating kirimase project on top of create-next-app over and over again, just to learn what is was doing. I wish that is a website like [shacn/ui's doc](https://ui.shadcn.com/docs) but for Kirimase. For copy-pasting, referencing and learning how to build together a Next.js app with different techs.

So here you go, create-next-diff show cases different ways to add technologies on top of create-next-app. I can't promise it just works. I can't promise it's as magical as Rails/Django etc. But it hopefully saves you some hours.

## shacnui, Drizzle, Lucia
1. Create next app. [PR](https://github.com/andthezhang/create-next-diff/pull/4).
2. Add drizzle with postgres and postgres.js. [PR](https://github.com/andthezhang/create-next-diff/pull/1)
3. Add shadcnui. [PR](https://github.com/andthezhang/create-next-diff/pull/2)
4. Add Lucia Auth. [PR](https://github.com/andthezhang/create-next-diff/pull/3)