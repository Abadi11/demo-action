# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `name`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `greeting`

How we greeted you.

## Example usage

```yaml
uses: actions/demo-action@e76147da8e5c81eaf017dede5645551d4b94427b
with:
  name: 'Mona the Octocat'
```