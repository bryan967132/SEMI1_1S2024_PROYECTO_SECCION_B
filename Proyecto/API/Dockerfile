FROM python:3-alpine

WORKDIR /app

ENV RDS_HOST=proyecto-seminario1.c7gm4e482f9t.us-east-2.rds.amazonaws.com
ENV RDS_USER=admin
ENV RDS_PASS=IHQCK05YT9zh51xZGSYWAA
ENV RDS_DATABASE=proyecto
ENV S3_BUCKET=proyecto-semi1-b-g4
ENV AWS_ACCESS_KEY_ID=AKIAQ3EGP7ZOD2ULDAMC
ENV AWS_SECRET_ACCESS_KEY=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
ENV REK_ACCESS_KEY=AKIAQ3EGP7ZOPATXFTMZ
ENV REK_SECRET_KEY=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
ENV REK_REGION=us-east-2
ENV TRANSLATE_ACCESS_KEY=AKIAQ3EGP7ZOA2OWYUS7
ENV TRANSLATE_SECRET_KEY=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
ENV TRANSLATE_REGION=us-east-2
ENV AWS_ACCESS_KEY_ID_LEX=AKIAQ3EGP7ZOGQJMCOV5
ENV AWS_SECRET_ACCESS_KEY_LEX=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
ENV BOT_ID=LLH34BZDB1
ENV BOT_ALIAS_ID=TSTALIASID
ENV LOCALE_ID=es_419
ENV SESSION_ID=100

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

EXPOSE 4000

CMD ["ash", "-c", "python App1.py"]