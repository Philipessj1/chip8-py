# chip8-py

Emulador de CHIP-8 escrito em Python, feito para aprender como CPUs e emuladores funcionam.

## Como rodar

```bash
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
python main.py roms/1-chip8-logo.ch8
```

## Status

- [ ] Ciclo buscar-decodificar-executar
- [ ] Fonte embutida e desenho de sprites
- [ ] Instruções restantes
- [ ] Teclado, timers e som
- [ ] Testes

## Créditos

ROMs de teste: [Timendus/chip8-test-suite](https://github.com/Timendus/chip8-test-suite).