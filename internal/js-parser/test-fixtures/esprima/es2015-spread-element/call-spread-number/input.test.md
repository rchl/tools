# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-spread-element > call-spread-number`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-spread-element/call-spread-number/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-spread-element/call-spread-number/input.js"
		end: Object {
			column: 0
			index: 10
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-spread-element/call-spread-number/input.js"
				end: Object {
					column: 9
					index: 9
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				loc: Object {
					filename: "esprima/es2015-spread-element/call-spread-number/input.js"
					end: Object {
						column: 8
						index: 8
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "f"
					loc: Object {
						filename: "esprima/es2015-spread-element/call-spread-number/input.js"
						identifierName: "f"
						end: Object {
							column: 1
							index: 1
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
				}
				arguments: Array [
					JSSpreadElement {
						loc: Object {
							filename: "esprima/es2015-spread-element/call-spread-number/input.js"
							end: Object {
								column: 7
								index: 7
								line: 1
							}
							start: Object {
								column: 2
								index: 2
								line: 1
							}
						}
						argument: JSNumericLiteral {
							value: 0.5
							format: undefined
							loc: Object {
								filename: "esprima/es2015-spread-element/call-spread-number/input.js"
								end: Object {
									column: 7
									index: 7
									line: 1
								}
								start: Object {
									column: 5
									index: 5
									line: 1
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```