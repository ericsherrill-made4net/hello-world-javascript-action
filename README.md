# Hello world javascript action
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fericsherrill-made4net%2Fhello-world-javascript-action.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fericsherrill-made4net%2Fhello-world-javascript-action?ref=badge_shield)


This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@e76147da8e5c81eaf017dede5645551d4b94427b
with:
  who-to-greet: 'Mona the Octocat'
```


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fericsherrill-made4net%2Fhello-world-javascript-action.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fericsherrill-made4net%2Fhello-world-javascript-action?ref=badge_large)