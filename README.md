# Terminal rectangle patterns

**C exercise** · Five rush variants draw different border styles in a terminal using character output.

## Build and use

```sh
cc ft_putchar.c rush00.c main.c -o rush
./rush
```

The executable uses the example or prompts shown in the source.

## Implementation note

Build one rushNN.c variant at a time because each defines rush(). The included main currently calls rush(5, 5).

Source: [`rush00.c`](rush00.c). [License](LICENSE).
