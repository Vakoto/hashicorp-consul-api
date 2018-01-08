# Hashicorp Consul API
I was looking for an OpenAPI for the Hashicorp Consul API (https://www.consul.io/api/index.html) for use in one of my government projects. During my search I found this thread about OpenAPI (fka Swagger) on Consul's Github Issues (https://github.com/hashicorp/consul/issues/555).

They say they don't support "Swagger Docs", but another user had created an API Blueprint, and resulting Apiary API documentation for the API (https://consul.docs.apiary.io/).

I have taken the API Blueprint and converted to OpenAPI using APIMATIC API Transformer, so that I can use the OpenAPI in my project documentation, loading into Postman for sharing with team members, testing, monitoring, and some other applications.

While it would be nice if Hashicorp Consul would maintain their own machine readable definition, this is the best we have. It is far from complete or verified, so if you improve upon it, please submit a pull request to improve upon it for everyone else.

Thanks - @kinlane
