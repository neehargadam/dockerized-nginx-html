docker build -t neehar-nginx-html .
docker tag neehar-nginx-html 975050024946.dkr.ecr.ap-northeast-2.amazonaws.com/neehar-nginx-html-repo:latest
docker push 975050024946.dkr.ecr.ap-northeast-2.amazonaws.com/neehar-nginx-html-repo:latest

