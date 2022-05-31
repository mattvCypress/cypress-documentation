---
title: Opening the App
---

<Alert type="info">

## <Icon name="graduation-cap"></Icon> What you'll learn

- How to start the Cypress app from the command line
- How to start your testing journey with the Launchpad
- How to choose a testing type
- How to launch a browser

</Alert>

## `cypress open`

If you used `npm` to install, Cypress has now been installed to your
`./node_modules` directory, with its binary executable accessible from
`./node_modules/.bin`.

Now you can open Cypress from your **project root** one of the following ways:

**The long way with the full path**

```shell
./node_modules/.bin/cypress open
```

**Or with the shortcut using `npm bin`**

```shell
$(npm bin)/cypress open
```

**Or by using `npx`**

**note**: [npx](https://www.npmjs.com/package/npx) is included with `npm > v5.2`
or can be installed separately.

```shell
npx cypress open
```

**Or by using `yarn`**

```shell
yarn run cypress open
```

After a moment, the Cypress App will launch.

## The Launchpad

<DocsImage src="/img/guides/getting-started/opening-the-app/launchpad.png" alt="The Launchpad window"></DocsImage>

Your Cypress testing journey begins with the Launchpad. Its job is to guide you
through the decisions and configuration tasks you need to complete before you
start writing your first test.

If this is your first time using Cypress it will take you through the following
steps in order.

### Choosing a Testing Type

<DocsImage src="/img/guides/getting-started/opening-the-app/choose-testing-type.png" alt="The Launchpad test type selector"></DocsImage>

The Launchpad presents you with your biggest decision first: What type of
testing shall I do?
[End-to-End Testing](/guides/core-concepts/testing-types#What-is-End-to-end-Testing),
where I run my whole application and visit pages to test them? Or
[Component Testing](/guides/core-concepts/testing-types#What-is-Component-Testing),
where I mount individual components of my app and test them in isolation?

For more background on this critical decision, read
[Testing Types](/guides/core-concepts/testing-types). Alternatively, if you're
not sure which type you want and just want to get on with your testing journey,
just choose End-to-End for now - you can always change this later!

### Quick Configuration

<DocsImage src="/img/guides/getting-started/opening-the-app/scaffolded-files.png" alt="The Launchpad scaffolded files list"></DocsImage>

On the next step, the Launchpad will scaffold out a set of configuration files
appropriate to your chosen testing type, and the changes will be listed for you
to review. For more information about the generated config check out the
[Cypress configuration reference](/guides/references/configuration), or you can
just scroll down and hit "Continue".

### Launching a Browser

<DocsImage src="/img/guides/getting-started/opening-the-app/select-browser.png" alt="The Launchpad browser selector"></DocsImage>

Lastly, you're presented with the list of compatible browsers Cypress found on
your system. To understand more about your options here, see
[our guide on launching browsers](/guides/guides/launching-browsers). Again,
don't sweat it, you can switch browsers whenever you want. Now <strong>MASH THAT
START BUTTON!</strong>

## Next Steps

Time to get testing! If you chose
[to start with E2E testing, go here](/guides/end-to-end-testing/writing-your-first-end-to-end-test).
Alternatively, if you decided
[to try component testing, go here](/guides/component-testing/writing-your-first-component-test).