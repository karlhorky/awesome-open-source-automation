# Awesome Open Source Automation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

List of impressive projects in open source automation.

## Contents

- [Automated issue creation](#automated-issue-creation)
- [Reproduction templates](#reproduction-templates)
- [Reproduction generators](#reproduction-generators)
- [Fully automated reproduction creation](#fully-automated-reproduction-creation)

## Automated issue creation

- [Bun automatic crash reporter](https://bun.sh/blog/bun-report-is-buns-new-crash-reporter)

## Reproduction templates

Starter templates to make it easier for contributors to create minimal reproductions of bugs:

- [Next.js (CodeSandbox)](https://codesandbox.io/p/sandbox/github/vercel/next.js/tree/canary/examples/reproduction-template)
- [Testing Library](https://github.com/testing-library/dom-testing-library-template)
- [Ent](https://github.com/ent/bug)
- [ESLint Stylistic](https://github.com/eslint-community/eslint-stylistic-repro-template)
- [Rspack](https://github.com/web-infra-dev/rspack-repro)
- [Renode](https://github.com/renode/renode-issue-reproduction-template)
- Vue Test Utils:
  - [issue creation template](https://github.com/vuejs/test-utils/blob/1cdd7ae5a973e8a2de8eef8c22159bc0cc97f911/.github/ISSUE_TEMPLATE/bug_report.md?plain=1#L16-L19)
  - [repro template on StackBlitz](https://stackblitz.com/github/vuejs/create-vue-templates/tree/main/typescript-vitest?file=src%2Fcomponents%2F__tests__%2FHelloWorld.spec.ts)
- [`shadcn-svelte`](https://github.com/huntabyte/shadcn-repro-template)
- [Ant Design (CodeSandbox)](https://codesandbox.io/s/antd-reproduction-template-forked-jyh2k9) [Link to docs](https://ant-design-3x.gitee.io/docs/react/getting-started#1.-Create-one-codesandbox:~:text=Visit%20http%3A//u.ant.design/codesandbox%2Drepro%20to%20create%20a%20codesandbox.%20Don%27t%20forget%20to%20press%20the%20save%20button.)
- [Apollo GraphQL](https://github.com/apollographql/next-apollo-example)

## Reproduction generators

Configurable generator web apps or CLIs to make it easier for contributors to create reproductions of bugs:

- [Storybook](https://storybook.js.org/docs/contribute/how-to-reproduce#initial-setup) 
- [Porsche Design (uses StackBlitz)](https://twitter.com/stackblitz/status/1648341661762633729)

## Fully automated reproduction creation

Automated capture of minimal reproductions of bugs without user effort:

- [Bun](https://twitter.com/jarredsumner/status/1781214396263661985)
