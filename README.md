# Talisman Online Python

Scripts, funções e módulos que eu uso para criar bots no jogo Talisman Online.

### Youtube
[https://www.youtube.com/@tonyr0xx](https://www.youtube.com/@tonyr0xx)

### PIX
`dae13311-4775-4973-849f-ad7d17ccbe8c`

### PAYPAL
`tonirogerio7@gmail.com`

### DISCORD
`tonirogerio7`

## Módulo Pointers
**Configure o id de processo antes de testar as funções.

```python
# Testando o código
pid = 972  # Substitua 972 pelo PID do processo correto
```

## Módulo Keyboard

**Exemplo de como enviar uma tecla para o jogo:**

1. Definir o `hwnd` da janela. Exemplo: `hwnd = 972`. Esse será o alvo, ou seja, a janela do jogo que receberá o comando.
2. Definir uma tecla. Exemplo: `next_target = 'TAB'`

**Comando para enviar a tecla TAB usando o módulo `keyboard.py`:**
```python
send(hwnd, next_target)
```



