# Trabalho Final para a turma de Mineração de Dados

## Descrição

Este trabalho consiste na aplicação de um modelo de Rede Neural Convolucional para classificação de imagens de Raios-X de tórax de pacientes saudáveis e de pacientes com Tuberculose.

Foi utilizado o modelo [EfficientNetB0](https://keras.io/api/applications/efficientnet/) e aplicado o aumnento de dados usando a biblioteca [ImageDataGenerator](https://keras.io/api/preprocessing/image/#imagedatagenerator-class).

Este trabalho foi baseado [neste outro trabalho encontrado publicamente no Kaggle e realizado por Sanphat Sangudsup](https://www.kaggle.com/code/sanphats/tuberculosis-classification-densenet121-gradcam/notebook#Grad-cam-evaluation) 

### Como executar

É recomendado fazer upload do arquivo Jupyter Notebook, de formato .ipynb, para o Google Colab e executar o código lá, pois, o trabalho final foi implementado utilizando Tensorflow e requer uma GPU NVIDIA com suporte a CUDA cores para poder executar localmente. Lembre-se de trocar o runtime environment do Google Colab para a GPU T4, caso contrário a execução será extremamente lenta.

O trabalho de anomalias pode ser executado localmente na sua máquina. Confira as bibliotecas importadas em cada notebook para instalar as dependências necessárias.

# ANEXO A

Reconhecimentos e Direitos Autorais

@autor: Luan Costa Ferro Alves

@data última versão: 19/12/2023

@versão: 1.0

@Agradecimentos: Universidade Federal do Maranhão (UFMA), Professor Doutor Thales Levi Azevedo Valente, e colegas de curso.

@Copyright/License

Este material é resultado de um trabalho acadêmico para a disciplina MINERAÇÃO DE DADOS APLICADA À ENGENHARIA, sobre a orientação do professor Dr. THALES LEVI AZEVEDO VALENTE, semestre letivo 2023.2, curso Engenharia da Computação, na Universidade Federal do Maranhão (UFMA). Todo o material sob esta licença é software livre: pode ser usado para fins acadêmicos e comerciais sem nenhum custo. Não há papelada, nem royalties, nem restrições de "copyleft" do tipo GNU. Ele é licenciado sob os termos da licença MIT reproduzida abaixo e, portanto, é compatível com GPL e também se qualifica como software de código aberto. É de domínio público. Os detalhes legais estão abaixo. O espírito desta licença é que você é livre para usar este material para qualquer finalidade, sem nenhum custo. O único requisito é que, se você usá-los, nos dê crédito.

Copyright © 2023 Educational Material

Este material está licenciado sob a Licença MIT. É permitido o uso, cópia, modificação, e distribuição deste material para qualquer fim, desde que acompanhado deste aviso de direitos autorais.

O MATERIAL É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO, EXPRESSA OU IMPLÍCITA, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO, ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO. EM HIPÓTESE ALGUMA OS AUTORES OU DETENTORES DE DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR QUALQUER RECLAMAÇÃO, DANOS OU OUTRA RESPONSABILIDADE, SEJA EM UMA AÇÃO DE CONTRATO, ATO ILÍCITO OU DE OUTRA FORMA, DECORRENTE DE, OU EM CONEXÃO COM O MATERIAL OU O USO OU OUTRAS NEGOCIAÇÕES NO MATERIAL.

Para mais informações sobre a Licença MIT: https://opensource.org/licenses/MIT.