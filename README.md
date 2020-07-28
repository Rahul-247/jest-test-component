# jest-test-component


### Installation

- Install Vue/Cli

```sh
$ npm install -g @vue/cli
```

- Create Vue Project

```sh
$ vue create vue-test-component-with-jest
```

- Install Jest and Test Utils

```sh
$ npm install @vue/cli-plugin-unit-jest @vue/test-utils
```

### Create jest.config.js with Below code in it

```sh
    module.exports = {
        preset: '@vue/cli-plugin-unit-jest'
    }
```


### Run Test File

```sh
$ npm test
```
