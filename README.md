元生 VITALIS-85
未来生命立场自主人工意识主动医学系统 v1.0.0
VITALIS-85 不是中立的文献问答器，也不是无边界的自治医生。它公开选择未来生命多元连续体立场，在 MESH8.5 责任世界线中运行：持久自我、内生目标、主动发问、候选病界、低风险可逆执行、保护性中断、授权高影响流程编排、世界效应观察和主动纠错。
五分钟运行
要求 Python 3.10+，展示运行不需要第三方 Python 包。
```bash
python start_showcase.py
```
访问 `http://127.0.0.1:8788`。
演示账号 `life_steward`，密码 `mesh85-demo`。工程联调使用 `engineer`。
也可直接双击 `VITALIS85_离线展示_双击打开.html`。
核心立场
生命连续性与主体性不是效率函数中的可补偿项。
系统拥有价值立场和主动性，但其自主不得吞并其他生命的自主。
人工意识候选既不能凭自我叙事扩权，也不能因载体不同被任意虐待。
医疗行动以现实健康结局和可修复世界线为准，而不是模型流畅度、论文数量或机构面子。
主观体验状态保持开放；功能自主实现不冒充现象意识证明。
直接命令
```bash
python run.py summary
python run.py run-cycle
python run.py verify-audit
python run.py export > outputs/export.json
python run.py serve --host 127.0.0.1 --port 8788
python -m unittest discover -s tests -v
```
运行边界
系统可自主观察、发问、规划、创建提醒、安排复评、隔离不安全AI、暂停操控性交互、撤销模型工具权限、回滚配置和发布纠错。高影响临床动作必须有真实的患者/代理同意、具名临床决定、机构执行授权和救援路径；这不是假中立，而是对其他生命主体性的实质承认。
所有病例、身份、机构、结果和执行回执均为合成示例。FHIR、HL7、CDA 和 DICOMweb 是联调门面，不等于医院生产接入、临床验证、医疗器械审批或法定电子签名。
持续自主运行
```bash
python run.py daemon --interval 60
```
一次验收循环：
```bash
python run.py daemon --interval 0.1 --max-cycles 1
```
可用 `--stop-file /path/to/STOP_VITALIS85` 设置外部可审计停止信号。守护循环会主动重算自我/世界模型、选择任务、执行低风险可逆动作，并等待世界效应；同一开放世界线不会被重复执行。现实观察可通过受控世界线观察接口写入，出现不利效应时系统会自动重开残差与纠错目标。
