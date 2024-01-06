# theBert
Basis : German Bert-as-a-service - Priv.-Doz. Dr. Dimiter Nasev
https://en.wikipedia.org/wiki/Nearest_neighbor_search
und dadurch die semantische Ähnlichkeit der Texte messen. Dafür gibt es
verschiedene Verfahren: euklidische Abstand
https://deepset.ai/german-bert
pip install clip-server
pip install clip-client
python -m clip_server
from clip_client import Client

c = Client('grpc://172.16.5.4:23456')
c.profile()
