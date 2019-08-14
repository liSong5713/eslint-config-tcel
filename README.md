# eslint-config-tcel ![image](https://img.shields.io/npm/l/eslint-config-tcel.svg)
> 同城艺龙酒店微信小程序代码规范 基于[eslint-config-standard](https://github.com/standard/eslint-config-standard), 规则请查看 [Rules](https://standardjs.com/rules-esla.html)

## NOTE

### 首先选择一款喜欢的IDE.建议vscode webstorm
- [ ] [参照vscode与webstorm集成eslint ](https://github.com/masterkong/blog/issues/8) 

> eslint-conifg-tcel 已经集成prettier并解决eslint与prettier规范冲突问题
> 



## Install


```
npm i eslint-config-tcel -D
```


## Usage

- 在项目根目录下创建 .eslintrc，然后添加以下代码
 （确保安装eslint-config-tcel，eslint会自动去node_modules 中找eslint-config-tcel）
```
{
  "extends": "eslint-config-tcel"
}

```
## Learn More

- [eslint](https://eslint.org/docs/developer-guide/shareable-configs)
- 代码规范参考 [standard代码规范](https://standardjs.com/rules-esla.html)  [airbnb代码规范](https://github.com/airbnb/javascript)
- [codereview标准流程](https://github.com/features/code-review/)

