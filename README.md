# theBert
Basis : German Bert-as-a-service - Priv.-Doz. Dr. Dimiter Nasev
https://en.wikipedia.org/wiki/Nearest_neighbor_search
und dadurch die semantische Ähnlichkeit der Texte messen. Dafür gibt es
verschiedene Verfahren: euklidische Abstand
https://deepset.ai/german-bert
pip install clip-server
pip install clip-client
python -m clip_server   # startet den clip server
from clip_client import Client

c = Client('grpc://172.16.5.4:23456')
c.profile()

pip install numpy   # speichern und laden der embeddings
pip install matplotlib  # https://numpy.org/devdocs/user/quickstart.html

https://rom1504.medium.com/semantic-search-with-embeddings-index-anything-8fb18556443c
https://huggingface.co/blog/getting-started-with-embeddings
https://www.tensorflow.org/text/guide/word_embeddings
https://www.elastic.co/search-labs/blog/articles/how-to-deploy-nlp-text-embeddings-and-vector-search
https://dev.to/chroline/leveraging-vector-embeddings-and-similarity-search-to-supplement-chatgpts-training-data-3ip4  # das ist gut! nutzt numpy und sieht einfach aus

pip install sentence_transformers faiss-cpu numpy
 WARNING: The script nltk is installed in '/usr/local/python/3.10.13/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script transformers-cli is installed in '/usr/local/python/3.10.13/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.

