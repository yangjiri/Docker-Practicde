# Dockerの練習
### インストール
<pre>
cd /home
git clone https://github.com/yangjiri/Docker-Practicde
cd Docker-Practicde
</pre>
### Run
<pre>
# Login For public Docker Repository
docker login
docker pull tnvjwldms/docker-practice
docker run -p 80:80 -v /home/Docker-Practicde/Project:/var/www/html tnvjwldms/docker-practice
</pre>

### 作業メモ
https://low-cap-2fc.notion.site/Dockerk-6ca0ee81fd5243f59943f637c2801405
