# cc1-pipeline

alexis.boisseau@etu.u-pec.fr

## Partie 1

1)
Il manque :
- un bucket S3 nommé "summary_destination" que je spécifie dans le fichier destination_s3_bucket.tf
- un kinesis stream nommé "datastream_ingestion" que je spécifie dans le fichier kinesis_datastream.tf

4)
L'application log dans un fichier le nombre de requêtes HTTP pour chaque Status et pour chaque minute.

5)
La partie « user_data » dans le fichier ec2.tf sert à spécifier des commandes qui vont s'éxécuter au lancent de la VM EC2.

6)
L'agent Kinesis permet de collecter des données stockées dans l'EC2 pour Amazon Kinesis.

7)
Un exemple du résultat du data pipeline se trouve dans le fichier "delivery-stream-summary-1-2021-11-16-15-14-00-b1df3a34-13da-4a0d-bfe3-25191d28e88e" dans le dossier "Fichiers réponses".

## Partie 2

1)L'ingestion est réalisée grâce à l'agent Kinesis et au 

## Partie 3

4)
Ce type de requête est requête SQL avec une fenêtre défilante ou glissante.

6)
La variable « email » sert à tager les ressources créées avec notre email pour pouvoir les identifier et les retrouver facilement dans AWS

