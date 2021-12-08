## Design

De acordo com o que foi estabelecido na etapa de concepção, agora iremos colocar em prática tudo que foi pensado afim de viabilizar o projeto. nesta etapa faz-se necessário estabelecer a quantidade de componentes e quais serão utilizados, além de suas ligações. Para tal, foi desenvolvido uma tabela com os componentes necessários, um diagrama com as ligações e uma planta baixa indicando onde cada sensor será posicionado.

## Componentes:

Quantidade  | Tecnologias
:---------:   | ------
1           | Placa Arduino MEGA 2560 R3
1           | Sensor de Umidade e Temperatura DHT11
1           | Sensor de gás MQ-2 inflamável e fumaça
1           | Micro Servo SG92R 9g TowerPro
1           | Módulo Sensor de Umidade/Nível Água Chuva
2 $         | Módulo Relé 5 V e um Canal
1           | Sensor ultrasônico HC-SR04
1           | Módulo Matriz de LED 8×8 com MAX7219
1           | Buzzer passivo
1           | Display LCD 16×2 I2C Backlight Azul
2 $         | Cooler 120mm
1 $         | Módulo e controle infravermelho

OBS: componentes com "$" ja possuo uma unidaded en casa

## Diagrama do circuito:

#### A imagem abaixo, demonstra as ligações de todos os sensores no Arduino mega, que é o principal do circuito, ele que irá comandar todos os sensores a realizarem suas devidas funções.

![circuito_projetoPI](https://user-images.githubusercontent.com/72568537/144244302-c21c677e-6a27-4c81-9242-cbf7ec70407d.png)


## Planta baixa:

#### A imagem abaixo, demonstra a planta  baixa da casa que será implementada no projeto integrador, indicando onde cada sensor irá ficar localizado.
![PlantaBaixaPI](https://user-images.githubusercontent.com/72568537/144092347-b723cf7f-8b9b-416f-bc28-9d13d2f5a1b6.png)
