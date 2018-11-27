
# AWS ES/Kibana Proxy

AWS ElasticSearch/Kibana Proxy to access your [AWS ES](https://aws.amazon.com/elasticsearch-service/) cluster. 


## Usage

Install the npm module 

    npm install -g aws-es-proxy-dub
    
Set AWS credentials
                          
    export AWS_ACCESS_KEY_ID=XXXXXXXXXXXXXXXXXXX
    export AWS_SECRET_ACCESS_KEY=XXXXXXXXXXXXXXXXXXX

Run the proxy (do not include the `http` or `https` from your `cluster-endpoint` or the proxy won't function)

    aws-es-proxy <cluster-endpoint>

Where cluster-endpoint can be either a URL (i.e. https://search-xxxxx.us-west-1.es.amazonaws.com) or a hostname (i.e. search-xxxxx.us-west-2.es.amazonaws.com). 



## Credits

Adopted from this [gist](https://gist.github.com/nakedible-p/ad95dfb1c16e75af1ad5). Thanks [@nakedible-p](https://github.com/nakedible-p)
