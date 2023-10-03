##Proposta de Fomento ao Aprendizado Contínuo em Sistemas Conversacionais

Introdução

Os sistemas conversacionais, como os chatbots, são amplamente utilizados em diversas aplicações  desde atendimento ao cliente até assistentes pessoais. No entanto, um desafio significativo enfrentado por esses sistemas é a falta de atualizaçao contínua de seus modelos. A medida que o mundo evolui, novas informaçoes e maneiras de expressar ideias surgem, tornando necessário que os modelos se adaptem a essas mudanças. O fenômeno onde o modelo não consegue se adaptar às mudanças no ambiente é conhecido como "concept drift". Esse desvio pode levar a respostas imprecisas ou desatualizadas o que acaba comprometendo a eficácia do sistema.


Solução Proposta

<img width="351" alt="Screenshot 2023-10-02 at 14 22 34" src="https://github.com/MrSchipRozen/Atividades/assets/99350292/b836dca6-dae5-4b38-976b-2400d985811f">


-Descrição textual das responsabilidades de cada bloco:

1 - Coleta de Dados: Este bloco é responsável por coletar novos dados e feedback dos usuários para conseguir identificar as  áreas onde o modelo pode estar desatualizado.

2 - Análise de Concept Drift: Aqui, os dados coletados são analisados para identificar se houve algum desvio no conceito. Se detectado, o sistema sinaliza a necessidade de re-treinamento.

3 - Re-treinamento do Modelo: Com base nos novos dados e feedback, o modelo é re-treinado para se adaptar às mudanças. 

4 - Validação: Antes de ser implantado, o modelo atualizado é testado para garantir que ainda atenda aos padroes de qualidade.

5 - Implantação: Uma vez validado o modelo atualizado é implantado, substituindo o modelo anterior.

Conclusão

O aprendizado contínuo é essencial para manter a relevância e eficácia dos sistemas conversacionais. Ao abordar o problema do "concept drift" e implementar uma estrutura que permite a atualização regular do modelo, podemos garantir que o sistema continue a fornecer respostas precisas e relevantes. A coleta contínua de dados e o re-treinamento regular do modelo podem ser desafiadores, mas são essenciais para manter a qualidade do serviço e uma entrga continua.


Referências Bibliográficas
Tianxing He, Jun Liu, Kyunghyun Cho, Myle Ott, Bing Liu, James Glass, and Fuchun Peng. Analyzing the forgetting problem in pretrain-ﬁnetuning of open-domain dialogue response models. In EACL, 2021.
Johannes Hoffart, Mohamed Amir Yosef, Ilaria Bordino, Hagen F¨urstenau, Manfred Pinkal, Marc Spaniol, Bilyana Taneva, Stefan Thater, and Gerhard Weikum. Robust disambiguation of named entities in text. In EMNLP, 2011.
Edward J Hu, Yelong Shen, Phillip Wallis, Zeyuan Allen-Zhu, Yuanzhi Li, Shean Wang, and Weizhu Chen. Lora: Low-rank adaptation of large language models. arXiv preprint arXiv:2106.09685, 2021.
Xisen Jin, Dejiao Zhang, Henghui Zhu, Wei Xiao, Shang-Wen Li, Xiaokai Wei, Andrew Arnold, and Xiang Ren. Lifelong pretraining: Continually adapting language models to emerging corpora. arXiv preprint arXiv:2110.08534, 2021.
Eunsol Choi, Jennimaria Palomaki, Matthew Lamm, Tom Kwiatkowski, Dipanjan Das, e Michael Collins. Decontextualization: Making sentences stand-alone. TACL, 9:447–461, 2021.
Damai Dai, Li Dong, Y. Hao, Zhifang Sui, e Furu Wei. Knowledge neurons in pretrained transformers. ArXiv, abs/2104.08696, 2021. Cyprien de Masson d’Autume, Sebastian Ruder, Lingpeng Kong, e Dani Yogatama. Episodic memory in lifelong language learning. Em NeurIPS, 2019.
Nicola De Cao, Wilker Aziz, e Ivan Titov. Editing factual knowledge in language models. Em EMNLP, 2021.
