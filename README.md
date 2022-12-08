# Protocolo Chord

O presente projeto é destinado a disciplina de Sistemas Distribuídos da Universidade Federal do Maranhão, com o propósito de implementar o protocolo Chord. 

### Definições rápidas

In computing, Chord is a protocol and algorithm for a peer-to-peer distributed hash table. A distributed hash table stores key-value pairs by assigning keys to different computers (known as "nodes"); a node will store the values for all the keys for which it is responsible. Chord specifies how keys are assigned to nodes, and how a node can discover the value for a given key by first locating the node responsible for that key.  [Wikipedia](https://en.wikipedia.org/wiki/Chord_(peer-to-peer))

Chord is based on consistent hashing, which assigns hash keys to nodes in a way that doesn't need to change much as nodes join and leave the system.  [ The University of Edinburgh](https://www.inf.ed.ac.uk/teaching/courses/ip/chord-desc.html#:~:text=Chord%20is%20based%20on%20consistent,paper%20by%20Stoica%20et%20al.)

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

```
- git clone https://github.com/vinisantosn/Projeto-Protocolo-Chord.git

- outra opção é baixar o repositório e replicar em sua máquina.

```

## ⚙️ Executando os testes

Para fazer os testes podemos fazer de duas maneiras:

1. Manualmente: 

    Com a ajuda de dois terminais execute os seguintes comandos
    ``` python3 Node_DHT.py numero_da_porta``` e em outro terminal ```python3 Client.py ```. A partir disso cria-se um nó inicial no anel. 
    
    Para os criação de próximos nós do anel temos o seguinte comando `python3 Node_DHT.py <número da porta do novo nó> <número da porta do nó existente>`
    
    Atenção no terminal do Client podemos fornecer entradas como o número da porta do nó ao qual o cliente deseja se conectar e, em seguida, a opção de acordo com a tarefa que o cliente deseja executar, como inserir, pesquisar, excluir dentre outras. 
    
2. Automático:

   Através de scripts que façam o papel do cliente inserindo em determinadas portas chaves e valores.

## 🛠️ Construído com

As ferramentas e tecnologias utilizadas na criação do projeto. 

* [Python](https://www.python.org/) - Linguagem de programação utilizada. 

## Implementado de 

* [Protocolo Chord - Uma tabela de hash distribuída](https://github.com/bhavinkotak07/chord_protocol)


## Materiais de estudo 

* [Chord (DHT) in Python](https://medium.com/princeton-systems-course/chord-dht-in-python-b8b8985cb80e)

* [Chord: A Scalable Peer-to-peer Lookup Protocol
for Internet Applications
](https://pdos.csail.mit.edu/papers/ton:chord/paper-ton.pdf)

* [python-chord
](https://github.com/gingaramo/python-chord)

* [CANChord: Reimplementing Chord in Python and adding CAN Realities to improve performance
](https://medium.com/princeton-systems-course/canchord-reimplementing-chord-in-python-and-adding-can-realities-to-improve-performance-ae3faa8b81de)

* [The implementation and performance of Chord
](https://core.ac.uk/download/pdf/157587916.pdf)

## Expressões de gratidão

* Agradeço a professora da disciplina supracitada que proporciona a prática de projetos, que em minha opnião fomenta mais conhecimento e auxilia no portifólio profissional. 
