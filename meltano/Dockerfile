FROM meltano/meltano

RUN meltano init project
WORKDIR project

COPY . .

RUN meltano install
