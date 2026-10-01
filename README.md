# desafio-step-function-aws
Este diagrama mostra um workflow do Amazon Step Functions para processamento distribuído de arquivos no S3. O fluxo inicia com um Map State, que percorre os arquivos e os envia para uma Lambda. Após o processamento, um Choice State valida os resultados: se válidos, são gravados no DynamoDB; caso contrário, seguem para falha.
