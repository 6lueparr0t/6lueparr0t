## How to run him

```
FROM man:asia-seoul

ENV NAME "Daehyun Lim"
ENV BIRTH 694083600 # 1991/12/30
ENV EDUCATION "Master's Degree of Computer Software in Yonsei Univ"

WORKDIR /web-developer

RUN rm -rf ./design-sense

COPY ./back-end-knowledge .
COPY ./some-devops-skill .
COPY ./much-front-end .
COPY ./AI-a-bit .

ADD coffee .

RUN sleep 21600 # 6 hour
RUN study --from=udemy
RUN make money --to=company --only=prod
RUN eat everything --except=seaweed-stem # 미역줄기
RUN workout --target=six-pack
#RUN play music webtoon youtube

ENTRYPOINT life start

EXPOSE https://blog.rgbplace.com
```
  
  [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F6lueparr0t&count_bg=%23338CFF&title_bg=%2301559A&icon=fluentd.svg&icon_color=%23FAFAFA&title=hits&edge_flat=true)](https://hits.seeyoufarm.com)
</div>
