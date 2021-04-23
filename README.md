# GmailResponse
GmailResponse
{
  "id": "1790000de925e63b",
  "threadId": "1790000de925e63b",
  "labelIds": [
    "IMPORTANT",
    "CATEGORY_UPDATES",
    "INBOX"
  ],
  "snippet": "Confirm your account to begin... \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c \u200c",
  "payload": {
    "partId": "",
    "mimeType": "multipart/related",
    "filename": "",
    "headers": [
      {
        "name": "Delivered-To",
        "value": "stefan.t+23440@condor-gaming.com"
      },
      {
        "name": "Received",
        "value": "by 2002:a9f:24c6:0:0:0:0:0 with SMTP id 64csp1735951uar;        Fri, 23 Apr 2021 11:32:07 -0700 (PDT)"
      },
      {
        "name": "X-Google-Smtp-Source",
        "value": "ABdhPJyUNzVodeBJHtUPROMhSqFrltdxfsq7UyXaiNVbQPUEhyOKDEHJo3AxhZ9S+7IHMcG56x0W"
      },
      {
        "name": "X-Received",
        "value": "by 2002:a05:600c:4fd0:: with SMTP id o16mr5553788wmq.140.1619202727546;        Fri, 23 Apr 2021 11:32:07 -0700 (PDT)"
      },
      {
        "name": "ARC-Seal",
        "value": "i=1; a=rsa-sha256; t=1619202727; cv=none;        d=google.com; s=arc-20160816;        b=f7SoGPMv63GYF/jq75rl/9vefW9sKQLCBC2WkDDj4hT8d37dyIXekpKd2kVt3VVc1N         Jz0S3fGHtPhqWjN2cwewh+2kHoBHLhfvSXS0VG4LN6sZkcIysldrVUuy+6z3hJaQ3A6r         Lvj4DqzjJwTBrIeLnsv4ffrc1fPaoMAuYhilYaGKHNOID0pkjQuVjUaSDd0UZex2bXm9         ZSCBcTj/+WaVQx9uAd0X361XkC1ROblHwpTCKp0j/DAIDZmdxWvT7sQUQpUiYb0MbVSW         nnnLaeEn2Zs2+1Uw6lqqS0pS1UEL3AT6hA31CQ9f2/XAFEQ1zCxZXPXuvJPBXrKBdkSK         ZspA=="
      },
      {
        "name": "ARC-Message-Signature",
        "value": "i=1; a=rsa-sha256; c=relaxed/relaxed; d=google.com; s=arc-20160816;        h=mime-version:date:subject:from:to:dkim-signature:message-id;        bh=7NgnNLSzm9sB0f6MSEeQXDHhYCwR3dSfcxzNvIrViWI=;        b=hUDLOYMw1zV0Z8RaLZ6rBfgcs8QkB7WlZt5u+VwxHnKnh4ikXF0r45XijJeS1TWrBw         iYsEVsamVjjU6E/04qjlKSUuJ0xKAlkLCFCmsCgKra4EJHIaQEoXwK4kjQHBnEZaVflK         bUhhUgWWtcWC23ZrAlXWqZhhVuok9PNaxgK0eHZpUifYZKHX+IJgY8JnFFALpwyeODP7         Nw+k+sGc/iRj27nZGHfeHxyusSWx8XDhtnKFIRpw10+9YDT4pTbwTAI2LFvkcSrwqSyr         awGUfKCGgX+rbLX1cLOPVcRDA+29MlPz1Ho2AYs55M1aCFtV7a4JeN8dAB9ND6wbZS4Q         8CzA=="
      },
      {
        "name": "ARC-Authentication-Results",
        "value": "i=1; mx.google.com;       dkim=pass header.i=@24bettle.com header.s=condor_mail1 header.b=JT3rObau;       spf=pass (google.com: domain of notification@24bettle.com designates 2a01:4f9:4b:16ce::2 as permitted sender) smtp.mailfrom=notification@24bettle.com;       dmarc=pass (p=NONE sp=NONE dis=NONE) header.from=24bettle.com"
      },
      {
        "name": "Return-Path",
        "value": "\u003cnotification@24bettle.com\u003e"
      },
      {
        "name": "Received",
        "value": "from mx.condor-gaming.com (mx.condor-gaming.com. [2a01:4f9:4b:16ce::2])        by mx.google.com with ESMTP id f11si6966293wry.465.2021.04.23.11.32.06        for \u003cstefan.t+23440@condor-gaming.com\u003e;        Fri, 23 Apr 2021 11:32:07 -0700 (PDT)"
      },
      {
        "name": "Received-SPF",
        "value": "pass (google.com: domain of notification@24bettle.com designates 2a01:4f9:4b:16ce::2 as permitted sender) client-ip=2a01:4f9:4b:16ce::2;"
      },
      {
        "name": "Authentication-Results",
        "value": "mx.google.com;       dkim=pass header.i=@24bettle.com header.s=condor_mail1 header.b=JT3rObau;       spf=pass (google.com: domain of notification@24bettle.com designates 2a01:4f9:4b:16ce::2 as permitted sender) smtp.mailfrom=notification@24bettle.com;       dmarc=pass (p=NONE sp=NONE dis=NONE) header.from=24bettle.com"
      },
      {
        "name": "Message-ID",
        "value": "\u003c608312a7.1c69fb81.ab55e.17b3SMTPIN_ADDED_MISSING@mx.google.com\u003e"
      },
      {
        "name": "Received",
        "value": "from localhost (webapp01.condor-gaming.com [IPv6:2a01:4f9:2b:2fc4::2]) by mx.condor-gaming.com (Postfix) with ESMTPSA id 5050E5402DA for \u003cstefan.t+23440@condor-gaming.com\u003e; Fri, 23 Apr 2021 20:32:06 +0200 (CEST)"
      },
      {
        "name": "DKIM-Signature",
        "value": "v=1; a=rsa-sha256; c=relaxed/simple; d=24bettle.com; s=condor_mail1; t=1619202726; bh=w8tEQRBVS6/nqXzwdIlhgbNKrWcnUvtjpTOdTra6RSU=; h=To:From:Subject:Date:From; b=JT3rObauWBd/gpZuAVvLflzd9YW78+Zxln5L+CVr9461jprnCQYhoXWWe7a4V7Mxd\t svUz30P5pI/UMwLnKBjGCBS6Uw8FeGeanHBK+G/PREy4cFXyehb99msjxnldXclLbh\t jQKcnhRYJihZ+L2zBjNGP6CDquvZGewIu90kpq0fI6EsNwRg/fr9JgWmNTjaUcKQC9\t UF3oj4KSG3R6CID7OIjhA9IXsNIh05wdfwY5yq1ZJ56NjHQwSneiEy02S/DMYuPXoj\t GjmKPtu9vHv7GchLydSpowGbTKfY/NxcmsIun/niosCJm/GsMpNbP9UDVQtf4euzpq\t DEfrJz+1zU7+Q=="
      },
      {
        "name": "To",
        "value": "stefan.t+23440@condor-gaming.com"
      },
      {
        "name": "From",
        "value": "24Bettle \u003cnotification@24bettle.com\u003e"
      },
      {
        "name": "Subject",
        "value": "Confirm & enjoy, Stefan23440"
      },
      {
        "name": "Date",
        "value": "Fri, 23 Apr 2021 18:32:06 +0000"
      },
      {
        "name": "Content-Type",
        "value": "multipart/related; boundary=\"=_88c01d32e1cd285b20095bfd1e688eca\""
      },
      {
        "name": "MIME-Version",
        "value": "1.0"
      }
    ],
    "body": {
      "size": 0
    },
    "parts": [
      {
        "partId": "0",
        "mimeType": "multipart/alternative",
        "filename": "",
        "headers": [
          {
            "name": "Content-Type",
            "value": "multipart/alternative; boundary=\"=_bccfbfd440ec22e2720eba2cb5f4543d\""
          },
          {
            "name": "Content-Transfer-Encoding",
            "value": "8bit"
          }
        ],
        "body": {
          "size": 0
        },
        "parts": [
          {
            "partId": "0.0",
            "mimeType": "text/plain",
            "filename": "",
            "headers": [
              {
                "name": "Content-Type",
                "value": "text/plain; charset=UTF-8"
              },
              {
                "name": "Content-Transfer-Encoding",
                "value": "quoted-printable"
              }
            ],
            "body": {
              "size": 457,
              "data": "SGVsbG8gU3RlZmFuMjM0NDAsCgpIaXQgdGhlIGxpbmsgdG8gY29uZmlybSB5b3VyIHNoaW55LCBuZXcgYWNjb3VudCBhbmQgZW50ZXIgMjRCZXR0bGUgLSBhIG5ldyBkaW1lbnNpb24gb2YgYXdlc29tZSEKCltDT05GSVJNXShodHRwczovL3d3dy4yNGJldHRsZS5jb20vcmVnaXN0ZXIvY29uZmlybT90b2tlbj1lQUVkanNjTkJFRU13MXJ5T0xzY3glMkY1THVNWDlKRUNnT0hzQ0NJQ01HbjFxMUVlZHMyRmZYNHV4MnBHVVptQlk4bDBhRjVJZ2p1YjJ3bGNaZ3UwV1dFOFN0OEdlZUlEbkR1UnJaN2JtZ21SN21kOUxNc2FtbWtINzZjZnhCRkFoTTd0SWFKTThwM2lyUlZ4dkV1a2J6aHhTRHFiJTJCcGZoVUVWcU9yVDR1R3F2cGw0eDJPWmxqVCUyRkY2bW5KaFBIVDlSZXZEdUoxeiUyRk13WnpacjIxWDFLV3JlVmVYaEZTNFFUdHFUZXJ3cERrdk5CeUpwRHMwYTFHQ2w5TUFUbTclMkZYTzN3JTJGQSUyQlZ1eikNCg=="
            }
          },
          {
            "partId": "0.1",
            "mimeType": "text/html",
            "filename": "",
            "headers": [
              {
                "name": "Content-Type",
                "value": "text/html; charset=UTF-8"
              },
              {
                "name": "Content-Transfer-Encoding",
                "value": "quoted-printable"
              }
            ],
            "body": {
              "size": 14024,
              "data": "PCFET0NUWVBFIGh0bWw-CjxodG1sIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hodG1sIiB4bWxuczpvPSJ1cm46c2NoZW1hcy1taWNyb3NvZnQtY29tOm9mZmljZTpvZmZpY2UiIHhtbG5zOnY9InVybjpzY2hlbWFzLW1pY3Jvc29mdC1jb206dm1sIj48aGVhZD48dGl0bGU-MjRCZXR0bGU8L3RpdGxlPjxtZXRhIGNvbnRlbnQ9ImxpZ2h0IG9ubHkiIG5hbWU9ImNvbG9yLXNjaGVtZSI-PG1ldGEgbmFtZT0iJnJkcXVvO3gtYXBwbGUtZGlzYWJsZS1tZXNzYWdlLXJlZm9ybWF0dGluZyZyZHF1bzsiPjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI-KiB7DQogICAgICAgIGZvbnQtZmFtaWx5OiAnU2Vnb2UgVUknLCBzYW5zLXNlcmlmOw0KICAgIH0NCg0KICAgIC5mdWxsLXdpZHRoIHsNCiAgICAgICAgbWF4LXdpZHRoOiA2MDBweCFpbXBvcnRhbnQ7DQogICAgICAgIHdpZHRoOiAxMDAlIWltcG9ydGFudDsNCiAgICB9DQoNCiAgICBAbWVkaWEgb25seSBzY3JlZW4gYW5kIChtYXgtd2lkdGg6IDYyMHB4KSB7DQoNCiAgICAgICAgLndyYXBwZXIgLnNlY3Rpb24gew0KICAgICAgICAgICAgd2lkdGg6IDEwMCU7DQogICAgICAgICAgICBtYXJnaW46IDFlbSAwICFpbXBvcnRhbnQ7DQogICAgICAgIH0NCg0KICAgICAgICAud3JhcHBlciAuY29sdW1uIHsNCiAgICAgICAgICAgIHdpZHRoOiAxMDAlOw0KICAgICAgICAgICAgZGlzcGxheTogYmxvY2s7DQogICAgICAgIH0NCg0KICAgICAgICAud3JhcHBlciAuY29sdW1uIGEgaW1nIHsNCiAgICAgICAgICAgIHdpZHRoOiAxMDAlICFpbXBvcnRhbnQ7DQogICAgICAgICAgICBkaXNwbGF5OiBibG9jazsNCiAgICAgICAgfQ0KDQogICAgICAgIC5ib3R0b20tbGlua3MtdGFibGUgew0KICAgICAgICAgICAgd2lkdGg6IDEwMCUgIWltcG9ydGFudDsNCiAgICAgICAgfQ0KDQogICAgICAgIC5zb2NpYWwtbGlua3MtdGFibGUgew0KICAgICAgICAgICAgd2lkdGg6IDEwMCUgIWltcG9ydGFudDsNCiAgICAgICAgfQ0KDQogICAgICAgIC5zb2NpYWwtbGlua3MtdGFibGUgdGJvZHkgdHIgew0KICAgICAgICAgICAgd2lkdGg6IDEwMCUhaW1wb3J0YW50Ow0KICAgICAgICB9DQoNCiAgICAgICAgLnNvY2lhbC1saW5rcy10YWJsZSB0Ym9keSB0ciB0ZCBhIGltZyB7DQogICAgICAgICAgICBtYXJnaW46IDAgYXV0bzsNCiAgICAgICAgfQ0KDQogICAgICAgIGJvZHkgPiBkaXYgew0KICAgICAgICAgICAgcGFkZGluZzogMCAwIWltcG9ydGFudDsNCiAgICAgICAgfQ0KDQogICAgICAgIC5tYWluLWJhbm5lciB7DQogICAgICAgICAgICBoZWlnaHQ6IDIwMHB4Ow0KICAgICAgICB9DQogICAgfQ0KDQogICAgQG1lZGlhIG9ubHkgc2NyZWVuIGFuZCAobWF4LXdpZHRoOiA0ODBweCkgew0KICAgICAgICAuYm90dG9tLWxpbmtzLXRhYmxlIHRib2R5IHRyIHsNCiAgICAgICAgICAgIGRpc3BsYXk6IGJsb2NrOw0KICAgICAgICAgICAgbWFyZ2luOiAxMHB4IDA7DQogICAgICAgIH0NCg0KICAgICAgICAuYm90dG9tLWxpbmtzLXRhYmxlIHRib2R5IHRyIHRkIHsNCiAgICAgICAgICAgIGRpc3BsYXk6IGJsb2NrOw0KICAgICAgICAgICAgd2lkdGg6IDEwMCUgIWltcG9ydGFudDsNCiAgICAgICAgICAgIHBhZGRpbmc6IDVweCAwOw0KICAgICAgICB9DQoNCiAgICAgICAgLmltYWdlLXNpemUtbW9iaWxlIHsNCiAgICAgICAgICAgIGhlaWdodDogMTUwcHggIWltcG9ydGFudDsNCiAgICAgICAgfQ0KDQogICAgICAgICNidXR0b24gew0KICAgICAgICAgICAgZm9udC1zaXplOiAxNXB4ICFpbXBvcnRhbnQ7DQogICAgICAgICAgICBwYWRkaW5nOiAxM3B4IDlweDsNCiAgICAgICAgfQ0KDQogICAgICAgIC5maXJzdC1iYW5uZXIgew0KICAgICAgICAgICAgaGVpZ2h0OiA0NXB4IWltcG9ydGFudDsNCiAgICAgICAgfQ0KDQogICAgICAgIC5tYWluLWJhbm5lciB7DQogICAgICAgICAgICBoZWlnaHQ6IDEzM3B4IWltcG9ydGFudDsNCiAgICAgICAgfQ0KDQogICAgICAgIC5mb290ZXItYm94IHNwYW4gew0KICAgICAgICAgICAgbWFyZ2luOiAxMHB4Ow0KICAgICAgICAgICAgZGlzcGxheTogYmxvY2shaW1wb3J0YW50Ow0KICAgICAgICAgICAgdGV4dC1hbGlnbjogY2VudGVyIWltcG9ydGFudDsNCiAgICAgICAgfQ0KICAgIH0NCiAgICA8L3N0eWxlPjwvaGVhZD48Ym9keSBjbGFzcz0iZnVsbC13aWR0aCIgZGF0YS1nci1leHQtaW5zdGFsbGVkPSIiIGRhdGEtbmV3LWdyLWMtcy1jaGVjay1sb2FkZWQ9IjE0Ljk5Ny4wIiBzdHlsZT0ibWF4LXdpZHRoOiA2MDBweDt3aWR0aDogMTAwJTtiYWNrZ3JvdW5kOiAjMzMzMzMzOyBtYXJnaW46IDAgYXV0bzsiPiA8ZGl2IHN0eWxlPSJvdmVyZmxvdzpoaWRkZW47Y29sb3I6dHJhbnNwYXJlbnQ7dmlzaWJpbGl0eTpoaWRkZW47bXNvLWhpZGU6YWxsO3dpZHRoOjA7Zm9udC1zaXplOjA7b3BhY2l0eTowO2hlaWdodDowOyI-Q29uZmlybSB5b3VyIGFjY291bnQgdG8gYmVnaW4uLi4mbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajsmbmJzcDsmenduajs8L2Rpdj4NCjxkaXYgY2xhc3M9ImZ1bGwtd2lkdGgiIHN0eWxlPSJ3aWR0aDogMTAwJTtwYWRkaW5nOiAxZW0gMDsiPjwhLS1baWYgbXNvIHwgSUVdPg0KICAgIDwvdGQ-PC90cj48L3RhYmxlPg0KICAgIDwhW2VuZGlmXS0tPjwhLS1baWYgbXNvIHwgSUVdPg0KICAgIDx0YWJsZSBjbGFzcz0iZnVsbC13aWR0aCIgYm9yZGVyPSIwIiBjZWxscGFkZGluZz0iMCIgY2VsbHNwYWNpbmc9IjAiIHdpZHRoPSI2MDAiIGFsaWduPSJjZW50ZXIiIHN0eWxlPSJ3aWR0aDogMTAwJTsiPg0KICAgICAgICA8dHIgc3R5bGU9IiAgICB3aWR0aDogMTAwJTsiPg0KICAgICAgICAgICAgPHRkIHN0eWxlPSJsaW5lLWhlaWdodDowcHg7Zm9udC1zaXplOjBweDttc28tbGluZS1oZWlnaHQtcnVsZTpleGFjdGx5OyI-DQogICAgPCFbZW5kaWZdLS0-DQo8ZGl2IGNsYXNzPSJmdWxsLXdpZHRoIiBzdHlsZT0iICAgIHdpZHRoOiAxMDAlO21hcmdpbjowIGF1dG87bWF4LXdpZHRoOjYwMHB4O2JhY2tncm91bmQ6IzMzMzMzMzsiPg0KPHRhYmxlIGFsaWduPSJjZW50ZXIiIGJvcmRlcj0iMCIgY2VsbHBhZGRpbmc9IjAiIGNlbGxzcGFjaW5nPSIwIiBjbGFzcz0iZnVsbC13aWR0aCIgc3R5bGU9ImZvbnQtc2l6ZTowcHg7d2lkdGg6MTAwJTtiYWNrZ3JvdW5kOiMxYjI5NDA7Ij48dGJvZHkgY2xhc3M9ImZ1bGwtd2lkdGgiPjx0ciBjbGFzcz0iZnVsbC13aWR0aCI-PHRkIGNsYXNzPSJmdWxsLXdpZHRoIiBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXI7dmVydGljYWwtYWxpZ246dG9wO2ZvbnQtc2l6ZTowcHg7cGFkZGluZzowcHg7Ij48IS0tW2lmIG1zbyB8IElFXT4NCiAgICAgICAgICAgICAgICAgICAgPHRhYmxlIGNsYXNzPSJmdWxsLXdpZHRoIiBib3JkZXI9IjAiIGNlbGxwYWRkaW5nPSIwIiBjZWxsc3BhY2luZz0iMCI-DQogICAgICAgICAgICAgICAgICAgICAgICA8dHIgY2xhc3M9ImZ1bGwtd2lkdGgiPg0KICAgICAgICAgICAgICAgICAgICAgICAgICAgIDx0ZCBjbGFzcz0iZnVsbC13aWR0aCIgc3R5bGU9InZlcnRpY2FsLWFsaWduOm1pZGRsZTt3aWR0aDo2MDBweDsiPg0KICAgICAgICAgICAgICAgICAgICA8IVtlbmRpZl0tLT4NCiAgICAgICAgICAgIDxkaXYgYXJpYS1sYWJlbGxlZGJ5PSJtai1jb2x1bW4tcGVyLTEwMCIgY2xhc3M9ImZ1bGwtd2lkdGgiIHN0eWxlPSJ2ZXJ0aWNhbC1hbGlnbjptaWRkbGU7ZGlzcGxheTppbmxpbmUtYmxvY2s7Zm9udC1zaXplOjEzcHg7dGV4dC1hbGlnbjpsZWZ0O3dpZHRoOjEwMCU7Ij4NCiAgICAgICAgICAgIDx0YWJsZSBib3JkZXI9IjAiIGNlbGxwYWRkaW5nPSIwIiBjZWxsc3BhY2luZz0iMCIgY2xhc3M9ImZ1bGwtd2lkdGgiIHN0eWxlPSJ2ZXJ0aWNhbC1hbGlnbjptaWRkbGU7IiB3aWR0aD0iMTAwJSI-PHRib2R5IGNsYXNzPSJmdWxsLXdpZHRoIj48dHI-PHRkIGFsaWduPSJjZW50ZXIiIHN0eWxlPSJ3b3JkLWJyZWFrOmJyZWFrLXdvcmQ7Zm9udC1zaXplOjBweDtwYWRkaW5nOjBweDsiPg0KICAgICAgICAgICAgICAgICAgICAgICAgPHRhYmxlIGFsaWduPSJjZW50ZXIiIGJvcmRlcj0iMCIgY2VsbHBhZGRpbmc9IjAiIGNlbGxzcGFjaW5nPSIwIiBzdHlsZT0iYm9yZGVyLWNvbGxhcHNlOmNvbGxhcHNlO2JvcmRlci1zcGFjaW5nOjBweDsiPjx0Ym9keT48IS0tICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICA8dHI-LS0-PCEtLSAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIDx0ZCBzdHlsZT0id2lkdGg6NjAwcHg7Ij4tLT48IS0tICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIDxhIGhyZWY9Imh0dHBzOi8vd3d3LjI0YmV0dGxlLmNvbS8_dXRtX3NvdXJjZT1zeXN0ZW0tZW1haWwmYW1wO3V0bV9tZWRpdW09SW1hZ2UiLS0-PCEtLSAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICB0YXJnZXQ9Il9ibGFuayIgPi0tPjwhLS0gICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIDxpbWcgYWx0PSIyNEJldHRsZSBMb2dvIi0tPjwhLS0gICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgc3JjPSJodHRwOi8vMjRiZXR0bGUuY29tL2ltYWdlcy9lbWFpbF9pbWFnZXMvYnV0dG9uLWdyYWRpZW50LXBpYy5wbmciLS0-PCEtLSAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICBzdHlsZT0ib3V0bGluZTogbm9uZTsgdGV4dC1kZWNvcmF0aW9uOiBub25lOyBjbGVhcjogYm90aDsgYm9yZGVyOiAwcHg7IG1heC13aWR0aDogNjQwcHg7IHdpZHRoOiA2MDBweDsgaGVpZ2h0OiAxMjJweDsgIi0tPjwhLS0gICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgdGl0bGU9IiIvPi0tPjwhLS0gICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgPC9hPi0tPjwhLS0gICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICA8L3RkPi0tPjwhLS0gICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIDwvdHI-LS0-PHRyPjx0ZCBzdHlsZT0id2lkdGg6NjUwcHgiPjxpbWcgY2xhc3M9ImZpcnN0LWJhbm5lciIgc3JjPSJjaWQ6NjlhMzhlYzNiYmU0MGI3NWNlNGVmMWEwYTE0Yjg1YjkiIHN0eWxlPSJvdXRsaW5lOiBub25lOyB0ZXh0LWRlY29yYXRpb246IG5vbmU7IGNsZWFyOiBib3RoOyBib3JkZXI6IDBweDsgbWF4LXdpZHRoOiA2MDBweDsgd2lkdGg6IDEwMCU7Ij48L3RkPg0KICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICA8L3RyPjwvdGJvZHk-PC90YWJsZT48L3RkPg0KICAgICAgICAgICAgICAgICAgICA8L3RyPjx0cj48dGQgYWxpZ249ImNlbnRlciIgc3R5bGU9IndvcmQtYnJlYWs6YnJlYWstd29yZDtmb250LXNpemU6MHB4O3BhZGRpbmc6MHB4OyI-Jm5ic3A7PC90ZD4NCiAgICAgICAgICAgICAgICAgICAgPC90cj48L3Rib2R5PjwvdGFibGU-PC9kaXY-DQogICAgICAgICAgICA8IS0tW2lmIG1zbyB8IElFXT4NCiAgICAgICAgICAgICAgICAgICAgPC90ZD48L3RyPjwvdGFibGU-DQogICAgICAgICAgICAgICAgICAgIDwhW2VuZGlmXS0tPjwvdGQ-DQogICAgICAgIDwvdHI-PC90Ym9keT48L3RhYmxlPjwvZGl2Pg0KPCEtLVtpZiBtc28gfCBJRV0-DQogICAgPC90ZD48L3RyPjwvdGFibGU-DQogICAgPCFbZW5kaWZdLS0-PCEtLVtpZiBtc28gfCBJRV0-DQogICAgPHRhYmxlIGJvcmRlcj0iMCIgY2VsbHBhZGRpbmc9IjAiIGNlbGxzcGFjaW5nPSIwIiB3aWR0aD0iNjAwIiBhbGlnbj0iY2VudGVyIiBzdHlsZT0id2lkdGg6NjAwcHg7Ij4NCiAgICAgICAgPHRyPg0KICAgICAgICAgICAgPHRkIHN0eWxlPSJsaW5lLWhlaWdodDowcHg7Zm9udC1zaXplOjBweDttc28tbGluZS1oZWlnaHQtcnVsZTpleGFjdGx5OyI-DQogICAgPCFbZW5kaWZdLS0-DQoNCjxkaXYgY2xhc3M9ImZ1bGwtd2lkdGgiIHN0eWxlPSIgICAgd2lkdGg6IDEwMCU7bWFyZ2luOjAgYXV0bzttYXgtd2lkdGg6NjAwcHg7YmFja2dyb3VuZDojZmZmOyI-DQo8dGFibGUgYm9yZGVyPSIwIiBjZWxscGFkZGluZz0iMCIgY2VsbHNwYWNpbmc9IjAiIGNsYXNzPSJmdWxsLXdpZHRoIiBzdHlsZT0icGFkZGluZzogMmVtIDJlbTt2ZXJ0aWNhbC1hbGlnbjptaWRkbGU7IiB3aWR0aD0iMTAwJSI-PHRib2R5IGNsYXNzPSJmdWxsLXdpZHRoIj48dHI-PHRkIGFsaWduPSJsZWZ0IiBzdHlsZT0id29yZC1icmVhazpicmVhay13b3JkO2ZvbnQtc2l6ZTowcHg7cGFkZGluZzowcHg7Ij4NCiAgICAgICAgICAgIDxkaXYgc3R5bGU9ImN1cnNvcjphdXRvO2NvbG9yOiMwMDAwMDA7Zm9udC1mYW1pbHk6VmVyZGFuYSwgc2Fucy1zZXJpZjtmb250LXNpemU6MjBweDtsaW5lLWhlaWdodDoyMHB4OyI-DQogICAgICAgICAgICA8cCBzdHlsZT0iZm9udC1zaXplOiAyMHB4OyBtYXJnaW46IDBweCAwcHggMTVweDsgY29sb3I6IHJnYig3NiwgNzYsIDc2KTsgdGV4dC1hbGlnbjogY2VudGVyOyI-SGVsbG8gU3RlZmFuMjM0NDAsPC9wPg0KICAgICAgICAgICAgPC9kaXY-DQogICAgICAgICAgICA8L3RkPg0KICAgICAgICA8L3RyPjx0ciBjbGFzcz0iZnVsbC13aWR0aCI-PHRkIGFsaWduPSJsZWZ0IiBzdHlsZT0id29yZC1icmVhazpicmVhay13b3JkO2ZvbnQtc2l6ZTowcHg7cGFkZGluZzowcHg7Ij4NCiAgICAgICAgICAgIDxkaXYgc3R5bGU9ImN1cnNvcjphdXRvO2NvbG9yOiMwMDAwMDA7Zm9udC1mYW1pbHk6VmVyZGFuYSwgc2Fucy1zZXJpZjtmb250LXNpemU6MTRweDtsaW5lLWhlaWdodDoyMHB4OyI-DQogICAgICAgICAgICA8dGFibGUgYm9yZGVyPSIwIiBjZWxscGFkZGluZz0iMCIgY2VsbHNwYWNpbmc9IjAiIHN0eWxlPSJmb250LXNpemU6IDEzcHg7IGJhY2tncm91bmQtY29sb3I6IHJnYigyNTUsIDI1NSwgMjU1KTsgdmVydGljYWwtYWxpZ246IG1pZGRsZTsiIHdpZHRoPSIxMDAlIj48dGJvZHk-PHRyPjx0ZCBhbGlnbj0ibGVmdCIgc3R5bGU9IndvcmQtYnJlYWs6IGJyZWFrLXdvcmQ7IGZvbnQtc2l6ZTogMHB4OyBwYWRkaW5nOiAwcHg7Ij4NCiAgICAgICAgICAgICAgICAgICAgICAgIDxkaXYgc3R5bGU9ImN1cnNvcjogYXV0bzsgZm9udC1mYW1pbHk6IFZlcmRhbmEsIHNhbnMtc2VyaWY7IGZvbnQtc2l6ZTogMTRweDsgbGluZS1oZWlnaHQ6IDIwcHg7Ij4NCiAgICAgICAgICAgICAgICAgICAgICAgIDx0YWJsZSBib3JkZXI9IjAiIGNlbGxwYWRkaW5nPSIwIiBjZWxsc3BhY2luZz0iMCIgc3R5bGU9ImZvbnQtZmFtaWx5OiBWZXJkYW5hLCBzYW5zLXNlcmlmOyBmb250LXNpemU6IDEzcHg7IGJhY2tncm91bmQtY29sb3I6IHJnYigyNTUsIDI1NSwgMjU1KTsgdmVydGljYWwtYWxpZ246IG1pZGRsZTsiIHdpZHRoPSIxMDAlIj48dGJvZHk-PHRyPjx0ZCBhbGlnbj0ibGVmdCIgc3R5bGU9IndvcmQtYnJlYWs6IGJyZWFrLXdvcmQ7IGZvbnQtc2l6ZTogMHB4OyBwYWRkaW5nOiAwcHg7Ij4NCiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIDxkaXYgc3R5bGU9ImN1cnNvcjogYXV0bzsgZm9udC1zaXplOiAxNHB4OyBsaW5lLWhlaWdodDogMjBweDsiPg0KICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgPHAgc3R5bGU9InRleHQtYWxpZ246IGNlbnRlcjsiPjxzcGFuIHN0eWxlPSJmb250LWZhbWlseTogdmVyZGFuYSwgZ2VuZXZhLCBzYW5zLXNlcmlmOyI-PHNwYW4gc3R5bGU9ImNvbG9yOiMzMzMzMzM7Ij5IaXQgdGhlIGxpbmsgdG8gY29uZmlybSB5b3VyIHNoaW55LCBuZXcgYWNjb3VudCBhbmQgZW50ZXIgPHN0cm9uZz4yNEJldHRsZSA8L3N0cm9uZz4tIGEgbmV3IGRpbWVuc2lvbiBvZiBhd2Vzb21lITwvc3Bhbj48L3NwYW4-PC9wPg0KICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgPC9kaXY-DQogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICA8L3RkPg0KICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICA8L3RyPjwvdGJvZHk-PC90YWJsZT48L2Rpdj4NCiAgICAgICAgICAgICAgICAgICAgICAgIDwvdGQ-DQogICAgICAgICAgICAgICAgICAgIDwvdHI-PC90Ym9keT48L3RhYmxlPjwvZGl2Pg0KICAgICAgICAgICAgPC90ZD4NCiAgICAgICAgPC90cj48dHI-PHRkIGFsaWduPSJjZW50ZXIiIHN0eWxlPSJ3b3JkLWJyZWFrOmJyZWFrLXdvcmQ7Zm9udC1zaXplOjBweDtwYWRkaW5nOjEwcHggMjVweDsiPg0KICAgICAgICAgICAgPHRhYmxlIGFsaWduPSJjZW50ZXIiIGJvcmRlcj0iMCIgY2VsbHBhZGRpbmc9IjAiIGNlbGxzcGFjaW5nPSIwIj48dGJvZHk-PHRyPjwhLS0gICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIHN0eWxlPSJib3JkZXI6IDNweCBzb2xpZCAjNEE4RkZGO2JveC1zaGFkb3c6IDBweCA1cHggMTBweCAwcHggcmdiYSg4NSwxMDgsMTA4LDEpO2Rpc3BsYXk6aW5saW5lLWJsb2NrO3RleHQtZGVjb3JhdGlvbjpub25lO2NvbG9yOndoaXRlO2ZvbnQtZmFtaWx5OlZlcmRhbmEsIHNhbnMtc2VyaWY7Zm9udC1zaXplOjIycHg7dGV4dC1zaGFkb3c6IDBweCAycHggMHB4ICMwMDAwMDA7bGluZS1oZWlnaHQ6IDIwcHg7Zm9udC13ZWlnaHQ6OTAwO21hcmdpbjowcHg7IHBhZGRpbmc6MjJweCAyM3B4OyBiYWNrZ3JvdW5kOiB0cmFuc3BhcmVudCBsaW5lYXItZ3JhZGllbnQoMTgwZGVnLCBSR0IoMTE4LCAxOTEsIDI1NCkgNDQlLCAjMUEzMzgwIDk3JSkgMCUgMCUgbm8tcmVwZWF0IHBhZGRpbmctYm94OyBuby1yZXBlYXQ6cGFkZGluZy1ib3g7Ym9yZGVyLXJhZGl1czogMzVweCItLT48dGQgYWxpZ249ImNlbnRlciIgYmdjb2xvcj0iIiBzdHlsZT0iYm9yZGVyLXJhZGl1czo2cHg7Y29sb3I6d2hpdGU7Y3Vyc29yOmF1dG87YmFja2dyb3VuZDogdXJsKGh0dHA6Ly8yNGJldHRsZS5jb20vaW1hZ2VzL2VtYWlsX2ltYWdlcy9idXR0b24tZ3JhZGllbnQtcGljLnBuZyk7YmFja2dyb3VuZC1zaXplOiAxMDAlIDEwMCU7IiB2YWxpZ249Im1pZGRsZSI-PGEgaHJlZj0iaHR0cHM6Ly93d3cuMjRiZXR0bGUuY29tL3JlZ2lzdGVyL2NvbmZpcm0_dG9rZW49ZUFFZGpzY05CRUVNdzFyeU9Mc2N4JTJGNUx1TVg5SkVDZ09Ic0NDSUNNR24xcTFFZWRzMkZmWDR1eDJwR1VabUJZOGwwYUY1SWdqdWIyd2xjWmd1MFdXRThTdDhHZWVJRG5EdVJyWjdibWdtUjdtZDlMTXNhbW1rSDc2Y2Z4QkZBaE03dElhSk04cDNpclJWeHZFdWtiemh4U0RxYiUyQnBmaFVFVnFPclQ0dUdxdnBsNHgyT1psalQlMkZGNm1uSmhQSFQ5UmV2RHVKMXolMkZNd1p6WnIyMVgxS1dyZVZlWGhGUzRRVHRxVGVyd3BEa3ZOQnlKcERzMGExR0NsOU1BVG03JTJGWE8zdyUyRkElMkJWdXoiIGlkPSJidXR0b24iIHN0eWxlPSJiYWNrZ3JvdW5kLWNvbG9yOiAjNDU4N0YxO2JhY2tncm91bmQtc2l6ZTogMTAwJSAxMDAlO2JhY2tncm91bmQtcmVwZWF0OiBuby1yZXBlYXQ7IGJhY2tncm91bmQtc2l6ZTogY292ZXI7Ym94LXNoYWRvdzogMHB4IDVweCAxMHB4IDBweCByZ2JhKDg1LDEwOCwxMDgsMC40KTtkaXNwbGF5OmlubGluZS1ibG9jazt0ZXh0LWRlY29yYXRpb246bm9uZTtjb2xvcjp3aGl0ZTtmb250LXNpemU6MjJweDtsaW5lLWhlaWdodDogMjBweDtmb250LXdlaWdodDo3MDA7bWFyZ2luOjBweDsgICAgcGFkZGluZzogMjJweCAzNXB4O2JvcmRlci1yYWRpdXM6IDM1cHg7Zm9udC1mYW1pbHk6ICdPc3dhbGQnLCBzYW5zLXNlcmlmOyAiIHRhcmdldD0iX2JsYW5rIj5DT05GSVJNPC9hPjwvdGQ-DQogICAgICAgICAgICAgICAgICAgIDwvdHI-PC90Ym9keT48L3RhYmxlPjwvdGQ-DQogICAgICAgIDwvdHI-PHRyPjx0ZCBhbGlnbj0iY2VudGVyIiBzdHlsZT0id29yZC1icmVhazpicmVhay13b3JkO2ZvbnQtc2l6ZTowcHg7cGFkZGluZzowcHg7Ij4NCiAgICAgICAgICAgIDxkaXYgc3R5bGU9ImN1cnNvcjphdXRvO2NvbG9yOiMwMDAwMDA7Zm9udC1mYW1pbHk6VmVyZGFuYSwgc2Fucy1zZXJpZjtmb250LXNpemU6MTRweDtsaW5lLWhlaWdodDoxNHB4OyI-DQogICAgICAgICAgICA8ZGl2IHN0eWxlPSJ0ZXh0LWFsaWduOiAtd2Via2l0LWNlbnRlcjsgYmFja2dyb3VuZC1jb2xvcjogcmdiKDI1NSwgMjU1LCAyNTUpOyBjdXJzb3I6IGF1dG87IGZvbnQtZmFtaWx5OiBWZXJkYW5hLCBzYW5zLXNlcmlmOyBmb250LXNpemU6IDE0cHg7IGxpbmUtaGVpZ2h0OiAxNHB4OyI-Jm5ic3A7PC9kaXY-DQogICAgICAgICAgICA8L2Rpdj4NCiAgICAgICAgICAgIDwvdGQ-DQogICAgICAgIDwvdHI-PC90Ym9keT48L3RhYmxlPjwvZGl2Pg0KDQo8ZGl2IGNsYXNzPSJmdWxsLXdpZHRoIiBzdHlsZT0ibWFyZ2luOjAgYXV0bzttYXgtd2lkdGg6NjAwcHg7Ij4mbmJzcDs8L2Rpdj4NCjwhLS1baWYgbXNvIHwgSUVdPg0KICAgIDwvdGQ-PC90cj48L3RhYmxlPg0KICAgIDwhW2VuZGlmXS0tPjwhLS1baWYgbXNvIHwgSUVdPg0KICAgIDx0YWJsZSBjbGFzcz0iZnVsbC13aWR0aCIgYm9yZGVyPSIwIiBjZWxscGFkZGluZz0iMCIgY2VsbHNwYWNpbmc9IjAiIHdpZHRoPSI2MDAiIGFsaWduPSJjZW50ZXIiIHN0eWxlPSJ3aWR0aDo2MDBweDsiPg0KICAgICAgICA8dHI-DQogICAgICAgICAgICA8dGQgc3R5bGU9ImxpbmUtaGVpZ2h0OjBweDtmb250LXNpemU6MHB4O21zby1saW5lLWhlaWdodC1ydWxlOmV4YWN0bHk7Ij4NCiAgICA8IVtlbmRpZl0tLT4NCg0KPGRpdiBjbGFzcz0iZnVsbC13aWR0aCIgc3R5bGU9Im1hcmdpbjowIGF1dG87bWF4LXdpZHRoOjYwMHB4O2JhY2tncm91bmQ6I2ZmZjsiPg0KPHRhYmxlIGFsaWduPSJjZW50ZXIiIGJvcmRlcj0iMCIgY2VsbHBhZGRpbmc9IjAiIGNlbGxzcGFjaW5nPSIwIiBjbGFzcz0iZnVsbC13aWR0aCIgc3R5bGU9ImZvbnQtc2l6ZTowcHg7d2lkdGg6MTAwJTtiYWNrZ3JvdW5kOiNmZmY7Ij48dGJvZHk-PHRyPjx0ZCBzdHlsZT0idGV4dC1hbGlnbjpjZW50ZXI7dmVydGljYWwtYWxpZ246dG9wO2ZvbnQtc2l6ZTowcHg7cGFkZGluZzowcHg7Ij48IS0tW2lmIG1zbyB8IElFXT4NCiAgICAgICAgICAgICAgICAgICAgPHRhYmxlIGJvcmRlcj0iMCIgY2VsbHBhZGRpbmc9IjAiIGNlbGxzcGFjaW5nPSIwIj4NCiAgICAgICAgICAgICAgICAgICAgICAgIDx0cj4NCiAgICAgICAgICAgICAgICAgICAgICAgICAgICA8dGQgc3R5bGU9InZlcnRpY2FsLWFsaWduOm1pZGRsZTt3aWR0aDozMDBweDsiPg0KICAgICAgICAgICAgICAgICAgICA8IVtlbmRpZl0tLT48IS0tW2lmIG1zbyB8IElFXT4NCiAgICAgICAgICAgICAgICAgICAgPC90ZD4NCiAgICAgICAgICAgICAgICAgICAgPHRkIHN0eWxlPSJ2ZXJ0aWNhbC1hbGlnbjptaWRkbGU7d2lkdGg6MzAwcHg7Ij4NCiAgICAgICAgICAgICAgICAgICAgPCFbZW5kaWZdLS0-PCEtLVtpZiBtc28gfCBJRV0-DQogICAgICAgICAgICAgICAgICAgIDwvdGQ-PC90cj48L3RhYmxlPg0KICAgICAgICAgICAgICAgICAgICA8IVtlbmRpZl0tLT48L3RkPg0KICAgICAgICA8L3RyPjwvdGJvZHk-PC90YWJsZT48L2Rpdj4NCjwhLS1baWYgbXNvIHwgSUVdPg0KICAgIDwvdGQ-PC90cj48L3RhYmxlPg0KICAgIDwhW2VuZGlmXS0tPjwvZGl2Pg0KPC9ib2R5PjwvaHRtbD4KDQo="
            }
          }
        ]
      },
      {
        "partId": "1",
        "mimeType": "image/png",
        "filename": "24header-image-2.png",
        "headers": [
          {
            "name": "Content-Type",
            "value": "image/png"
          },
          {
            "name": "Content-Transfer-Encoding",
            "value": "base64"
          },
          {
            "name": "Content-ID",
            "value": "\u003c69a38ec3bbe40b75ce4ef1a0a14b85b9\u003e"
          },
          {
            "name": "Content-Disposition",
            "value": "inline; filename=\"24header-image-2.png\""
          },
          {
            "name": "Content-Location",
            "value": "https://24bettle.com/images/banners/24header-image-2.png"
          }
        ],
        "body": {
          "attachmentId": "ANGjdJ9xJyrCL-FGhpep7wurVPAE2VBJOHbBZpTBKmZdp4JK6XwauPA-If61i9TV3XT8cjw9-hYbgzcUJ8L3kxuNcmSMigsdrv9Gf8eNysUK4bDhpBJpCI56v-fgN1jKY8H2t3J9ih4LRjJm9svLrav9Xba9_9rFDJi5Y_0wcNuQvCHld5XCIDIq-bSe0SlIeP1noTHlTkVgmiA6PZMTR0_iYnv6q0MhJRYiJr_OViShPor3fZBTZ2f41JNGByp9BqAopBdgneEeB1v0M_M3uLmpipCNFT5n-94YL3oKzcLBj6JSijrUo7SllG_cLxWp11Lex46oPCnHtct1QIG36JChnb7wr0hVYROMk-BDTX0QOYoTUHvk1su-tgtM15lp6kQdxnolZUJXAYECT32t",
          "size": 3624
        }
      }
    ]
  },
  "sizeEstimate": 25816,
  "historyId": "2827943",
  "internalDate": "1619202726000"
}

