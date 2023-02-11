Ingressing with k3s

kubectl create ns test-ingress-traefik

kubectl create configmap mysite-html --from-file index.html -n test-ingress-traefik

kubectl apply -f mysite.yaml -n test-ingress-traefik

http://k3s.n0-reply.com/

kubectl create configmap mydog-html --from-file html -n test-ingress-traefik

kubectl apply -f mydog.yaml -n test-ingress-traefik

http://k3s.n0-reply.com/mydog/

open http://k3s.n0-reply.com/mydog/

