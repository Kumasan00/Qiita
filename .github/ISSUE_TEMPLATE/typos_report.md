---
name: 誤字脱字報告
about: 誤字脱字報告のテンプレート
title: "~~誤字脱字報告"
labels: typos
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        誤字脱字報告ありがとうございます。以下の情報を記入してください。

  - type: textarea
    id: description
    attributes:
      label: 誤字脱字の箇所
      description: 誤字脱字の箇所を教えてください
      placeholder: 誤字脱字の箇所を教えてください
    validations:
      required: true

  - type: textarea
    id: reproduction
    attributes:
      label: 修正後(任意)
      description: 修正後に期待される文章を記載してください。
      placeholder: 修正後の文章
    validations:
      required: false

---


