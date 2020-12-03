# kio-speech-to-text-inception

# IBM watson
- https://cloud.ibm.com/apidocs/speech-to-text?code=node
- https://convertio.co/m4a-flac/
- 500 minutos free
- https://speech-to-text-demo.ng.bluemix.net/
- https://www.ibm.com/cloud/watson-speech-to-text/pricing


```sh
curl -X POST -u "apikey:{apikey}" \
--header "Content-Type: audio/flac" \
--data-binary @{path_to_file}prueba_es_watson.flac \
"{url}/v1/recognize"
```