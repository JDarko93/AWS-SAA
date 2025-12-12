## Content Delivery Networks (CDNs)
- This works as cache for requested info for web apps
- It can cache content and serve it to users within a certain region
- Reducing latency and workload on the origin server
- It can cache static content like HTML web pages that dont change often

### AWS CloudFront
- AWS service for CDN is CloudFront
- User requests content via a URL > 410+ CDN global servers < Origin Server
- It works by the users request first going to the CDN global servers to see if it has the content it is requesting. If not it will forward the request to the origin server and cache it
- The time it stays cached depends on what the caching is set to for your CDN configuration 

#### CloudFront data origins vary
- S3, EC2, ELB, Media Services, API Gateways, on-prem data, HTTP servers
- Custom code can run on CDN edge 
- CloudFront CDN is also optimised to enhance media streaming such as movies, audio as well as software patch deployment

### CloudFront Cache Behavior Settings 
- Configuraing CloudFront will mean thinking about origins and paths on it
- Ensuring HTTP requests are redirected to HTTPS
- Allowed HTTP methods can include header directives that determines how long things stay cached in cloudfront
- Object caching TTL (Time to Live) 