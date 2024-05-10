# spark

Caso rode no COLAB(Indico), não precisa fazer muita coisa para rodar. Apenas faça as instalações que estão no pip do código e coloque esse camarada:

from pyspark.sql import SparkSession

spark = SparkSession.builder \
    .master('local[*]') \
    .appName("Iniciando com Spark") \
    .getOrCreate()

Agora é só rodar e fazer seu projeto    
