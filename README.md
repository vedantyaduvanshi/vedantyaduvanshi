# HTB Metrics Badge Generator

Currently in the alpha stage. Keep an eye out for upcoming templates and updates, or contribute to the development!

<!--header-->
### 🧠 Hack The Box Stats

![HTB Metrics](htb-metrics.png)
<!--/header-->

## ℹ️ Examples workflows

```yaml
name: Example
uses: yonasuriv/htb-metrics@latest
with:
  filename: htb-metrics.classic.png
  token: ${{ secrets.HTB-METRICS_TOKEN }}
  userid: 000000
  template: default
```
