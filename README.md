## 6lueparr0t's Dockerfile

```
FROM man:asia-seoul AS daehyun-lim

ENV BIRTH 694083600 # 1991/12/30
ENV EDUCATION "Master's Degree of Computer Software in Yonsei Univ"

WORKDIR /web-developer

RUN rm -rf ./design-sense

COPY ./back-end-knowledge .
COPY ./some-devops-skill .
COPY ./much-front-end .
COPY ./AI-a-bit . --from=yonsei-univ

ADD coffee .

RUN coding
RUN make money --for=me,family,lover --only=production
RUN eat pork-cutlet homemade-kimchijjigae korea-ramyun --except=seaweed-stem # 미역줄기
RUN workout --target=six-pack
#RUN play webtoon youtube chzzk

ENTRYPOINT say "One for a line, a line for all."

EXPOSE https://6lueparr0t.github.io
```
