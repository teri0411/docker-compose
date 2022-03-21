# Apache HTTP server 이미지를 바탕으로 컨테이너를 실행한 후
# http://localhost로 접속했을 때 index.html이 표시되게 만드세요

FROM httpd:2.4
WORKDIR /usr/local/apache2/htdocs/
COPY ./index.html /usr/local/apache2/htdocs/
COPY ./script.js /usr/local/apache2/htdocs/



