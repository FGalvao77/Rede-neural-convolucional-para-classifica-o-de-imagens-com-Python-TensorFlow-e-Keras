# Rede neural convolucional para classificação de imagens com Python, TensorFlow e Keras

No aprendizado profundo, uma rede neural convolucional é uma classe de redes neurais profundas que têm sido usadas com grande sucesso em 
tarefas de visão computacional, como classificação de imagens, detecção de objetos, segmentação de imagens, ...

Os neurônios em uma camada convolucional não estão totalmente conectados a cada pixel na imagem de entrada, como em uma rede neural tradicional. 
Em vez disso, eles são conectados a um pequeno retângulo de pixels na imagem de entrada.

Por sua vez, cada neurônio da segunda camada convolucional está conectado apenas a outros neurônios localizados em uma região específica da primeira camada.

Com essa arquitetura, o modelo só precisa se concentrar nos pequenos detalhes da primeira camada oculta, como bordas, e depois montá-los em recursos 
mais elaborados na segunda camada e assim por diante.

Além disso, isso fará com que a rede neural convolucional tenha muito menos parâmetros do que uma rede totalmente conectada, 
útil para processar imagens de grande porte.

