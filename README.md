# Construção de um sistema de recomendação de musicas com Spark

- Análise dos dados
- Matriz de correlação
- PCA e StandartScaler
- Pipeline
- K-Means

    - from pyspark.sql import SparkSession
    - from pyspark import SparkFiles
    - import pyspark.sql.functions as f
    - import plotly.express as px
    - import plotly.graph_objects as go
    - from pyspark.ml.feature import VectorAssembler
    - from pyspark.ml.feature import StandardScaler
    - from pyspark.ml.feature import PCA
    - from pyspark.ml import Pipeline
    - from pyspark.ml.clustering import KMeans
    - from pyspark.ml.functions import vector_to_array
    - import numpy as np
    - from scipy.spatial.distance import euclidean
    - from pyspark.sql.types import FloatType
    - import spotipy
    - from spotipy.oauth2 import SpotifyOAuth, SpotifyClientCredentials
    - import matplotlib.pyplot as plt
    - from skimage import io