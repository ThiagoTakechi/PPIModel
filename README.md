# PPI Model

Repositório com a implementação em Python utilizada para a simulação do modelo de inibição pré-pulso (PPI) desenvolvidos no projeto de mestrado "MODELO COMPUTACIONAL PARA SIMULAÇÃO DO TESTE DE INIBIÇÃO PRÉ-PULSO: Interfaces com a Esquizofrenia" na Universidade Federal do ABC (UFABC).

O código disponibilizado neste repositório resolve numericamente pelo método de Euler o sistema de equações diferenciais ordinárias que representam a atividade das unidades que compõem a rede neural proposta para o PPI. Cada equação diferencial representa a atividade de uma estrutura do sistema nervoso ou a neurotransmissão dopaminérgica no núcleo accumbens.

## Terminology

Reposta de Sobressalto: resposta reflexa a um estímulo saliente de alta intensidade (luz forte, som alto, imagens abruptas) caracterizada por um padrão estereotípico de contrações musculares (em humanos: contração dos omboros, reflexo de piscas, contração do abdomen etc.; em roedores: encurtamento do tronco, contração das patas, fechamento dos olhos, etc.). Quando em resposta a um estímulo sonoro, é comumente chamado de resposta de sobressalto acútico (ou ASR, do inglês acoustic startle repsonse);

Filtro Sensório-Motor: função do sistema nervoso que previne a interferência no processamento de uma informação quando há uma resposta motora a outro estímulos;

Inibição Pré-Pulso: medida operacional do filtro sensório-motor. Quando o estímulo sonoro de alta intensidade (acima de 100 dB) que causa o ASR é precedido em milissegundos por um estímulo sonoro de menor intensidade e que não causa o sobressalto (e.g.: 75 dB), a amplitude do ASR é atenuada. Esta inibição do sobressalto pelo pré-pulso é chamada de inibição pré-pulso (ou PPI, do inglês prepulse inhibition);

Intervalo Inter-Estímulos: intervalo em milissegundos do pré-pulso e do pulso, também chamado ISI (interstimulus interval);

## Abbreviation 

Ch: cóclea/ cochlea;
CRN: Núcleo da raiz da cóclea/cochlear root nucleus;
CPRN: núcleo caudal pontino reticular/caudal pontine reticular nucleus;
MN: neurônio motor/motor neuron;
IC: colículo inferior/inferior colliculus;
SC: colículo superior/superior colliculus;
PPTg: núcleo pedúnculopontino tegmental/pedunculopontine tegmental nucleus;
mPFC: córtex pré-frontal medial/medial prefrontal cortex;
Amyg: amígdala/amygdala;
NAc: núcleo accumbens/nucleus accumbens;
VP: pálido ventral/ventral pallidum;
VTA: área tegmental ventral/ventral tegmental area.
