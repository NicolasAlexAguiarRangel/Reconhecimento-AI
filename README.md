
# Reconhecimento Facial e transformação de imagens em Dados no Azure ML

O Reconhecimento Facial e a transformação de imagens em dados são duas áreas fundamentais da Inteligência Artificial (IA) e do Aprendizado de Máquina (AM), e o Azure Machine Learning oferece ferramentas robustas para trabalhar com ambas.

Reconhecimento Facial é uma forma de IA que identifica ou verifica a identidade de uma pessoa a partir de uma imagem digital ou um padrão de vídeo. No Azure ML, você pode treinar modelos de aprendizado de máquina para realizar tarefas de reconhecimento facial, como identificar indivíduos específicos em imagens ou vídeos, ou determinar características como idade ou emoção a partir de imagens faciais.

A transformação de imagens em dados refere-se ao processo de converter imagens em uma forma que possa ser entendida e utilizada por algoritmos de aprendizado de máquina. Isso geralmente envolve a extração de características das imagens que podem ser usadas para treinar um modelo de aprendizado de máquina. No Azure ML, você pode usar bibliotecas como OpenCV ou PIL para processar imagens e extrair características úteis.

Ambas as áreas têm uma ampla gama de aplicações, desde segurança e vigilância até aplicações de saúde e varejo. No entanto, também levantam questões importantes sobre privacidade e ética. É crucial garantir que qualquer uso dessas tecnologias respeite a privacidade dos indivíduos e seja usado de maneira ética e responsável.


## Aprendizados

Exemplos de legendas e legendas densas:

## Criar um recurso de serviços de IA do Azure

Neste exercício, você usará o serviço de IA do Azure para explorar os recursos de reconhecimento óptico de caracteres do Azure AI Vision. Você usará o Vision Studio para experimentar extrair texto de imagens, sem precisar escrever nenhum código.

Um desafio comum de visão computacional é detectar e interpretar texto incorporado em uma imagem. Isso é conhecido como reconhecimento óptico de caracteres (OCR). Neste exercício, você usará um recurso de serviços de IA do Azure, que inclui os serviços de Visão de IA do Azure. Em seguida, você usará o Vision Studio para experimentar o OCR com diferentes tipos de imagens.

### Criar um recurso de serviços de IA do Azure

Você pode usar os recursos de OCR do Azure AI Vision com um recurso multisserviço dos serviços de IA do Azure. Se você ainda não tiver feito isso, crie um recurso de serviços de IA do Azure em sua assinatura do Azure.

1. Em outra guia do navegador, abra o portal do Azure em https://portal.azure.com, entrando com a conta da Microsoft associada à sua assinatura do Azure.

2. Clique no botão +Criar um recurso e procure serviços de IA do Azure. Selecione criar um plano de serviços de IA do Azure. Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:
   
    Comandos/configurações:

    Assinatura: sua assinatura do Azure.
    Grupo de recursos: selecione ou crie um grupo de   
    recursos com um nome exclusivo.
    Região: Leste dos EUA.
    Nome: insira um nome exclusivo.
    Nível de preços: Standard S0.
    Ao marcar esta caixa, reconheço que li e entendi 
    todos os termos abaixo: Selecionado.
    Selecione Revisar + criar e, em seguida, Criar e 
    aguarde a conclusão da implantação.

# imagem Implatação 

<img href="https://github.com/NicolasAlexAguiarRangel/Reconhecimento-AI/blob/main/Captura%20de%20tela%201.png?raw=true">


## Conectar seu recurso de serviço de IA do Azure ao Vision Studio

Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio.

1. Em outra guia do navegador, navegue até o Vision Studio em https://portal.vision.cognitive.azure.com.

2. Entre com sua conta e verifique se você está usando o mesmo diretório em que criou seu recurso de serviços de IA do Azure.

3.Na home page do Vision Studio, selecione Exibir todos os recursos no cabeçalho Introdução ao Vision.

## Imagem Introdução ao Vision 

<https://github.com/NicolasAlexAguiarRangel/Reconhecimento-AI/blob/main/Captura%20de%20tela%202.png?raw=true>

4. Na página Selecione um recurso para trabalhar, passe o cursor do mouse sobre o recurso criado acima na lista e marque a caixa à esquerda do nome do recurso e selecione Selecionar como recurso padrão.

    // Nota: Se o recurso não estiver listado, talvez seja necessário 
    atualizar a página. // 

# Imagem Recurso Padrão

<https://github.com/NicolasAlexAguiarRangel/Reconhecimento-AI/blob/main/Captura%20de%20tela%203.png?raw=true>

# Imagem Deploy

<https://github.com/NicolasAlexAguiarRangel/Reconhecimento-AI/blob/main/Captura%20de%20tela%202024-03-16%20223043.png?raw=true>

## A resposta JSON a seguir ilustra o que a API do Analysis 4.0 retorna ao descrever a imagem de exemplo com base em seus recursos visuais.


## Imagem legendas Densas
 
<https://github.com/NicolasAlexAguiarRangel/Reconhecimento-AI/blob/main/inputs/imagem%202.png?raw=true>

## Descrição

Uma mulher sentada em um sofá com um laptop e um cachorro
Um cachorro em pé em um tapete
Uma pessoa segurando um laptop
Uma mulher sentada em um sofá com um laptop
Um copo branco em uma superfície listrada vermelha e branca
Uma mulher sentada em um sofá com um laptop e um cachorro olhando para ele
Um close up de uma superfície de madeira
Um banquinho de madeira com um copo branco no topo
Uma mulher olhando para um laptop
Uma imagem desfocada de uma janela

## Arrumar 

Se você não pretende fazer mais exercícios, exclua todos os recursos que não são mais necessários. Isso evita o acúmulo de custos desnecessários.

1. Abra o portal do Azure e selecione o grupo de recursos que contém o recurso que você criou.

2. Selecione o recurso e selecione Excluir e, em seguida, Sim para confirmar. O recurso é excluído.
