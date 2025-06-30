面向学术分析与学者画像的知识图谱数据集ScholarKG，请访问https://github.com/svenzhi/ScholarKG

# 📚 ScholarInfoNER 中文学者信息识别数据集

## 📝 数据集简介

**ScholarInfoNER** 是一个面向中文场景构建的学者信息命名实体识别（NER）数据集，旨在支持学术人物画像、科研知识图谱构建等自然语言处理任务。数据来源于公开渠道（如高校官网、教师主页等），通过大语言模型提示词结合人工审校完成实体标注，覆盖多种学者相关实体类型。

本数据集可用于：

- 命名实体识别模型训练与评估
- 学者画像与知识图谱构建任务
- 中文信息抽取与领域语言理解研究

---

## 📦 数据内容与格式

数据采用 **BIOES** 标注格式，按行存储为 `conll` 风格文本（`.txt` 文件），共划分为三部分：

- `train.txt`：训练集  
- `dev.txt`：开发集  
- `test.txt`：测试集  

### ✅ 实体类别（示例）：
- `NAME`：姓名  
- `TITLE`：职称  
- `ORG`：单位/组织  
- `EDU`：教育背景  
- `RESEARCH`：研究方向
- 具体类别信息请查看`ScholarInfoNER.json`

### ✅ 标注示例：

```
张三	B-NAME
，	O
河南	B-LOC
开封	I-LOC
人	O
。	O
```

---

## ⚖️ 开源协议与使用说明

本数据集基于 **[CC BY 4.0 署名协议](https://creativecommons.org/licenses/by/4.0/)** 发布。

您可以自由复制、修改、分发和用于商业用途，但 **必须署名原始作者和来源**：

> 数据集作者：XXX
> 
> 来源链接：https://github.com/svenzhi/ScholarInfoNER  

### 📌 使用者注意事项

> 本数据集中包含部分来源于公开渠道的学者个人信息（如姓名、单位、教育背景等），**仅供学术研究用途**。  
> 使用者应自行评估其使用场景是否涉及隐私、伦理或合规风险，**在必要时，应获得相关学者的明确同意**。  
> 对因使用本数据集引发的任何法律、道德或其他责任，数据集发布者不承担责任。

---

## 📊 数据统计

请查看`ScholarInfoNER.json`。



---

## 🔁 引用方式（Citation）

如在学术论文中使用本数据集，请按以下格式引用：

```bibtex
@dataset{your_id,
  title       = {},
  author      = {},
  year        = {2025},
  url         = {https://github.com/svenzhi/ScholarInfoNER},
  publisher   = {},
  license     = {CC BY 4.0}
}
```

---

## 📫 联系方式

如对数据集有任何问题或建议，欢迎联系作者：

- 📧 邮箱：  
- 🔗 项目主页：https://github.com/svenzhi/ScholarInfoNER
