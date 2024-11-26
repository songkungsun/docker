# Nginx 기반 이미지 사용
FROM nginx:latest

# 작업 디렉터리 설정
WORKDIR /usr/share/nginx/html

# 로컬 파일을 컨테이너로 복사
COPY index.html /usr/share/nginx/html/index.html

# Nginx는 기본적으로 포트 80에서 실행됨
EXPOSE 80

# 컨테이너 실행 시 Nginx 실행
CMD ["nginx", "-g", "daemon off;"]
