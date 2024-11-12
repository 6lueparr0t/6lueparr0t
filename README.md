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
  
  [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F6lueparr0t&count_bg=%23338CFF&title_bg=%2301559A&icon=fluentd.svg&icon_color=%23FAFAFA&title=hits&edge_flat=true)](https://hits.seeyoufarm.com)
</div>
