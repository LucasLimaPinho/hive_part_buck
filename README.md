Técnicas de otimização para Hive: Desnormalização, Partition and Bucketing.

  Partition: realiza separação física (partições) em pastas do HDFS. 
             Otimiza consultas - não serve para consultas simples como select * from sales;
             
  Bucketing: número fixo de partições. Não muda conforme os dados;
              divide fisicamente de forma balanceada em partições;
              
              
    PARTITION        |        BUCKETING
 
 Baixa Cardinalidade | Cardinalidade alta e variável
 Um atributo ou mais | Apenas um atributo
