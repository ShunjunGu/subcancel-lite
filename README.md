# 支付宝「智能体涌现奖」· 扣费清理助手

目录：`/workspace/paid-ops/batch11-2026-10-28/alipay-agent/`  
更新：2026-10-28（上海时间）

## 本包文件
| 文件 | 说明 |
| --- | --- |
| `index.html` | 可单文件打开的静态 Demo（手机浏览器友好） |
| `DESIGN.md` | 名称、价值、3 场景、3 组对话、边界 |
| `prompt.md` | QMuse/活动用完整系统提示词 |
| `SUBMIT_COPY.md` | 活动提交简介草稿 |
| `README.md` | 本说明 |

## 本地预览
```bash
# 方式1：直接用浏览器打开
xdg-open index.html   # 或双击 / 手机传文件打开

# 方式2：本地静态服务
cd /workspace/paid-ops/batch11-2026-10-28/alipay-agent
python3 -m http.server 8765
# 浏览器打开 http://127.0.0.1:8765/
```

## 演示步骤
1. 打开页面 → 点「示例 A/B/C」→「解析扣费」
2. 查看表格：商户、金额、周期、扣款日、取消路径、置信度
3. 可选「复制结果表」；不要填写真实密码/卡号

## 规则核实（公开网页，部分待核）
来源：IT之家 2026-09-10 https://www.ithome.com/0/1000/848.htm
- 已核：发展基金 / 年度大奖结构；交可公开 URL；个人「生活好帮手」/商家「消费新体验」
- **待核（须用户支付宝 App→阿宝「智能体涌现奖」截图）**：首期「价值 5000 元」是否现金、首轮截止、名额、实名与收款

## 提交清单
- [x] 实施：静态 Demo + 提示词 + 设计说明 + 提交文案
- [x] 公网 URL：https://shunjungu.github.io/subcancel-lite/ （GitHub Pages，2026-10-28 已通）
- [ ] 【用户】App 内截完整规则
- [ ] 【用户】活动内报名并提交 URL（**代理人未代提交**）

## 已部署
- 仓库：https://github.com/ShunjunGu/subcancel-lite
- Pages：https://shunjungu.github.io/subcancel-lite/ （HTTP 200 已核，上海时间 2026-10-28）
- **未**在支付宝活动内报名/提交。
