# Evolução do Projeto IDE Wandi para Arduino AVR

## 1. Primeiros Passos
- Inicialmente tentei programar uma linguagem qualquer junto com o Arduino.
- Problema: não havia comunicação direta com a placa e o objetivo era **evitar o Arduino IDE**.
- Primeira tentativa: criar interface no navegador com simulador 3D para projetos físicos (ex: braço robótico).
- Resultado: inviável, pois não existia integração entre código e hardware, apenas comunicação via porta serial.

## 2. Tentativa na Unity
- Criação de braço robótico 3D na Unity.
- Problema: comunicação limitada apenas via UI e porta serial.
- Não havia programação direta do Arduino.
- Insight: **editor de código é prioridade**, especialmente para controlar o braço robótico Wandi.

## 3. Evolução com Python
- Ingresso na universidade trouxe nova perspectiva e habilidades.
- Uso de Python ampliou possibilidades:
  - Controle direto do Arduino via **PyFirmata**.
  - Possibilidade de abstrair programação complexa.
- Objetivo atual: **desenvolver uma mini IDE** que atenda todas as necessidades de programação do Wandi.

## 4. Limitações do PyFirmata2
- PyFirmata2 permite **controle direto da placa** sem escrever código Arduino.
- Limitação: **não grava código permanentemente na placa**.
  - Tudo que é executado desaparece ao desligar a placa.

## 5. Próximos Passos: Compiladores e AST
- Estudo de tradutores e compiladores para criar **ponte entre Python e Arduino C/C++**.
- Uso do **AST do Python** para:
  - Analisar código Python.
  - Gerar código Arduino compatível.
  - Permitir upload permanente na placa.
- Objetivo: criar uma **nova linguagem baseada em Python**, adaptada para programação de microcontroladores.

## 6. Resumo da Evolução
1. Unity + simulador 3D → falha por falta de integração com código.
2. Controle via porta serial → viável, mas dependente de UI, sem código persistente.
3. Python + PyFirmata → controle direto, mas sem gravação permanente.
4. Mini IDE → base pronta para edição, execução e comunicação serial.
5. Ponte Python → Arduino via AST → futuro upload de código gravável na placa.

## 7. Observações Técnicas
- O passo do AST é essencial para:
  - Detectar chamadas de funções de hardware.
  - Mapear para funções Arduino.
  - Gerar código C/C++ compilável.
- Possibilidade futura de explorar MicroPython para AVR.
- Meta: IDE completa que combina **Python-like syntax** com **controle real e persistente do Arduino**.

