# Exercício 2.1
Para cada item de termos de <strong>performance</strong>, pesquisar exemplos de medições.

<strong>1. Tempo de Resposta</strong>
> [Is this all the information we need? While this information helps us to get a better understanding 
which kind of problem we have, we can do better finding out where the problem exactly is – or better 
which application component caused the problem. Therefore we split the response time – and its components – 
by application components like our business layer, database layer etc. 
This creates a matrix of the different timing components and layers.](https://www.dynatrace.com/blog/week-9-how-to-measure-application-performance/)

![Exemplo de medição de response time, separado por componente](https://dt-cdn.net/wp-content/uploads/migration/APIResponseTimeBreakdown.png)

---

<strong>2. Responsividade:</strong>
[Time To First Byte (TTFB). This measures the responsiveness of your mobile app. 
It indicates how fast your app is able to 
launch and get the first responses from the back end servers](https://bitbar.com/mobile-performance-index-3-measuring-app-performance-metrics-that-matter/)

---

<strong>3. Latência:</strong>
[f it was captured, the TCP handshake will be the first packets displayed. 
If the capture was taken client-side, use the delta time displayed timer to measure the delay between the 
SYN and SYN / ACK packets. This gives you a benchmark network roundtrip time.](http://www.lovemytool.com/blog/2015/03/wireshark-tip-finding-slow-application-response-time-by-chris-greer.html)

![Imagem com exemplos de medição de latência](http://www.lovemytool.com/.a/6a00e008d95770883401bb080acba3970d-pi)

---

<strong>4. Throughput:</strong>
[Often we see the workload to a web application measured by throughput. 
It’s a way of quantifying the volume of requests/responses in relation to time. 
Transactions per second or TPS is the most common ratio used](https://www.neotys.com/blog/how-to-test-application-throughput/)

---

<strong>5. Carga:</strong>
[If you have an average visit length of 5 minutes, a single user could create 60 min / 5 min = 12 visits per hour. 
To get to the target number of 1000 visits/visitors per hour, you need 1000 visits / 12 visits per user = 84 concurrent user.](https://sqa.stackexchange.com/questions/1508/calculate-peak-concurrent-users-on-a-website)

---

<strong>6. Sensibilidade à carga / degradação:</strong>

---