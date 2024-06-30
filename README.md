# Oficina_Mecanica
Projeto modelagem de dados

1.	Cliente:
o	Representa o proprietário do veículo que busca serviços de manutenção.
o	Tem um relacionamento com a “Ordem de Serviço” (OS).
2.	Ordem de Serviço (OS):
o	É gerada quando o cliente leva seu veículo para a oficina.
o	Contém informações sobre o serviço solicitado, como tipo de manutenção (preventiva ou corretiva).
o	É entregue ao cliente para aprovação.
o	Se aprovada, a OS é executada.
3.	Mecânico/Eletricista:
o	Identifica a manutenção a ser executada no veículo.
o	Pode ser associado a várias OSs.
o	Tem conhecimento sobre os tipos de manutenção.
4.	Tipo de Manutenção:
o	Representa as categorias de serviços (preventiva ou corretiva).
o	Pode ser vinculado a várias OSs.
5.	Autopeça:
o	Fornecedora de materiais para a execução da manutenção.
o	Pode estar relacionada a várias OSs.
6.	Cliente/Executante:
o	Cada cliente ou pessoa responsável pela execução da manutenção é cadastrado no sistema.
o	O valor do serviço é calculado e apresentado ao cliente para aprovação ou reprovação.
7.	Execução da Manutenção:
o	Se aprovada, a manutenção é realizada.
o	Os materiais fornecidos pela autopeça são utilizados.
o	O status da OS é atualizado para refletir a conclusão da manutenção.
