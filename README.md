# π νλ¦¬μ¨λ³΄λ© νλ‘ νΈμλ μ±λ¦°μ§ 2μ - TypeScript

<div align='center'>


## μκΈ°μκ° βπ¨βπ»

<div>
    <a href="https://interesting-longan-2b3.notion.site/ee7224efb8b143eda8a57e8e96fc9b7a">
        <img src="https://img.shields.io/badge/Notion-white?&style=flat-square&logo=notion&logoColor=black"/>
    </a>
    <a href="https://velog.io/@100dongwoo">
        <img src="https://img.shields.io/badge/Velog-1DBF73?style=flat-square&logo=Vimeo&logoColor=white"/>
    </a>
</div>


</div>

### μλνμΈμ νλ‘ νΈ μλ κ°λ°μ λ°±λμ°μλλ€ π

- ν­μ μ±μ₯μ λͺ©λ§λΌ μλ κ°λ°μμλλ€.

- μ½λλ¦¬λ·°μ λ¦¬ν©ν λ§μ κ΄μ¬μ΄ λ§μ κ°λ°μμλλ€.

- μ±μ© κ³Όμ λ±μ μννλ©° μ€μ€λ‘μ λΆμ‘±ν λΆλΆμ μ΄λ²κΈ°νλ‘ μ°Ύμλ³΄κ³  μΆμ΅λλ€

- μν°λ μ΄λ²κΈ°νλ₯Ό ν΅ν΄μ νμμ€ν¬λ¦½νΈλ₯Ό νμ€ν μ΅ν νμΈ΅ μ±μ₯νκ³ μΆμ κ°λ°μμλλ€.



<br/>
<hr/>
μκ΅¬ μ¬ν­μ κ΅¬ννμ§ μκ³  μ€κ³λ§ν©λλ€.

- Todo μ±μ JSDocμΌλ‘ λ¬Έμννλ μ±λ¦°μ§ κ³Όμ μλλ€.
- λͺ¨λ  μκ΅¬μ¬ν­μ JSDocμ κΈ°λ°μΌλ‘ μνν©λλ€.
- μ μΆν  μ μ₯μ λͺμ wanted-pre-onboarding-challenge-fe-2λ‘ μμ±ν΄ μ£ΌμΈμ. (Public κΆν νμ)
- μμ±ν κ³Όμ μ μ μ₯μ λ§ν¬λ₯Ό λͺ¨μ§ λ§κ° ν μ€λ¬Έ μ‘°μ¬λ₯Ό ν΅ν΄ μ μΆν΄μ£ΌμΈμ. (κ°κ° μ μ€λ¬Έ μ‘°μ¬ λ§ν¬ μ λ¬ μμ )
- κ³Όμ  μν κ°μμ λ°λΌ κΈ°λ³Έμ μΈ νκ°κ° μ΄λ£¨μ΄μ§λ©°, μ»€λ¦¬νλΌ μ΄μ κ³Όμ μμ μ΅μνμ μμ€μ νμνκΈ° μν μ©λμλλ€.
- ν΄λΉ κ³Όμ μ λν ν΄μ€μ κ°κ° ν μ§νλ  μμ μλλ€.
- README.mdλ₯Ό κΌ­ μμ±ν΄ μ£ΌμΈμ. λ³ΈμΈμ λν μκ°λ νλ‘μ νΈ μκ° λ± μμ λ‘­κ² μμ±ν΄μ£Όμλ©΄ λ©λλ€.
- JSDoc νκ²½ κ΅¬μ±μ μ΄μν κ²½μ° [Boilerplate](https://github.com/pocojang/jsdoc-boilerplate)λ₯Ό μ΄μ©νμλ λ©λλ€

## π Requirements

### νμ μκ΅¬μ¬ν­

> μλμ Todo μ± μκ΅¬μ¬ν­μ μ°Έκ³ νμ¬

- νμν λ°μ΄ν°λ₯Ό λͺ¨λ λͺ¨λΈλ§νλ€.
- μ¬μ©λλ λͺ¨λ  ν¨μλ₯Ό `μ μΈλΆλ§` λ§λ λ€.
  - ν¨μ λ° ν΄λμ€μ λ΄λΆλ κ΅¬ννμ§ μμ΅λλ€.
- `JSDoc`μ νμ©ν΄ λ¬Έμννλ€.
- `GitHub Page`λ₯Ό νμ©ν΄ `JSDoc` μ μ  νμ΄μ§λ₯Ό λ°°ν¬νλ€.

### Todo

```
Todo {
  μμ΄λ(required),
  λ΄μ©(required),
  μλ£μ¬λΆ(required),
  μΉ΄νκ³ λ¦¬(required),
  νκ·Έλ€(optional),
}
```

#### CREATE
- ν  μΌμ μΆκ°ν  μ μλ€.
- λ΄μ©μμ΄ μΆκ°ν  μ μλ€.

#### READ
- λͺ¨λ  ν  μΌμ μ‘°νν  μ μλ€.
- IDλ₯Ό κΈ°λ°μΌλ‘ νΉμ  ν  μΌμ μ‘°νν  μ μλ€.

#### UPDATE
- IDλ₯Ό μ μΈν λͺ¨λ  μμ±μ μμ ν  μ μλ€.
- νΉμ  ν  μΌμ νΉμ  νκ·Έλ₯Ό μμ ν  μ μλ€.

#### DELETE
- IDλ₯Ό κΈ°λ°μΌλ‘ νΉμ  ν  μΌμ μ­μ ν  μ μλ€.
- λͺ¨λ  ν  μΌμ μ κ±°ν  μ μλ€.
- νΉμ  ν  μΌμ νΉμ  νκ·Έλ₯Ό μ­μ ν  μ μλ€.
- νΉμ  ν  μΌμ λͺ¨λ  νκ·Έλ₯Ό μ κ±°ν  μ μλ€.

#### Modeling (Shape)

```
Item {
  property(required),
  property(optional),
}
```

#### Reference

- [use JSDoc](https://jsdoc.app)
- [JSDoc Boilerplate](https://github.com/pocojang/jsdoc-boilerplate)
