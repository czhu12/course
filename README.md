# Internet

## Networking

### How does your browser load https://google.com?
1. DNS Lookup
`dscacheutil -q host -a name google.com`

2. ISP routing tables
Verizon -> Google

traceroute google.com

3. Establishes connection to port on destination computer

4. Makes HTTP Request (we can break this down further)
4.a TCP connection

5. Site sends back 1 HTML page

6. Browser loads the HTML page, which has tons of external links

7. This whole process is repeated for each of the external links (https://google.com/script.js)


### Web Infrastructure Patterns
1. Stateless deployments of web servers
2. Connects to a single database which stores all the data
3. 

### Deployment




