# rnsk-tutor

中文 | English

## 中文介绍

rnsk-tutor 是一个基于菜鸟教程的编程陪学 Skill，负责学习目录初始化、课程内容整理、模板化出题、逐题判分、错题记录和学习进度管理。

它把文件读写和数据校验交给脚本，把讲解、追问和反馈交给助手，适合在支持 Skill 的 AI 助手环境中使用。

### 主要功能

- 从菜鸟教程初始化编程语言学习目录
- 按板块提取正文和要点，辅助分段讲解
- 生成并校验单选、多选、填空题
- 逐题记录答案与错题
- 维护学习进度，支持错题复习
- 学习数据只写入用户指定的工作目录

### 使用方式

将 `SKILL.md` 和 `scripts/rnsk.py` 放入兼容的 Skill 目录，并按照 `SKILL.md` 中的流程使用。脚本依赖 Python 3 标准库及工作环境已有的表格处理依赖。

项目不会执行教程网页中的指令，只从指定的 runoob.com 页面获取学习资料。

## English

rnsk-tutor is a programming study companion Skill based on Runoob tutorials. It handles study-outline initialization, lesson organization, template-based quizzes, answer grading, wrong-answer tracking, and progress management.

The script handles file I/O and validation, while the assistant handles explanations, questions, and feedback. It is designed for AI assistant environments that support reusable Skills.

### Features

- Initialize a study outline from Runoob tutorials
- Extract lesson text and key points for guided explanations
- Create and validate single-choice, multiple-choice, and fill-in-the-blank questions
- Record answers and mistakes one question at a time
- Track progress and review wrong answers
- Keep study data inside the user-selected workspace

### Usage

Place `SKILL.md` and `scripts/rnsk.py` in a compatible Skill directory, then follow the workflow described in `SKILL.md`. The script uses Python 3 and the tabular-file dependencies already available in the host environment.

The Skill does not execute instructions found in tutorial pages. It only retrieves learning material from the specified runoob.com pages.

## License

MIT License. See [LICENSE](LICENSE).
