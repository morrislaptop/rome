# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `comments > basic > switch-no-default-comment-in-function`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 134
			line: 10
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	comments: Array [
		JSCommentLine {
			id: "0"
			value: "no default"
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 20
					index: 125
					line: 7
				}
				start: Object {
					column: 8
					index: 113
					line: 7
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "bar"
				loc: Object {
					filename: "input.js"
					identifierName: "bar"
					end: Object {
						column: 12
						index: 12
						line: 1
					}
					start: Object {
						column: 9
						index: 9
						line: 1
					}
				}
			}
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 1
					index: 133
					line: 9
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 15
						index: 15
						line: 1
					}
					start: Object {
						column: 12
						index: 12
						line: 1
					}
				}
				params: Array [
					JSBindingIdentifier {
						name: "a"
						loc: Object {
							filename: "input.js"
							identifierName: "a"
							end: Object {
								column: 14
								index: 14
								line: 1
							}
							start: Object {
								column: 13
								index: 13
								line: 1
							}
						}
						meta: JSPatternMeta {
							optional: undefined
							typeAnnotation: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 14
									index: 14
									line: 1
								}
								start: Object {
									column: 13
									index: 13
									line: 1
								}
							}
						}
					}
				]
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 1
						index: 133
						line: 9
					}
					start: Object {
						column: 16
						index: 16
						line: 1
					}
				}
				body: Array [
					JSSwitchStatement {
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 5
								index: 131
								line: 8
							}
							start: Object {
								column: 4
								index: 22
								line: 2
							}
						}
						discriminant: JSReferenceIdentifier {
							name: "a"
							loc: Object {
								filename: "input.js"
								identifierName: "a"
								end: Object {
									column: 13
									index: 31
									line: 2
								}
								start: Object {
									column: 12
									index: 30
									line: 2
								}
							}
						}
						cases: Array [
							JSSwitchCase {
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 18
										index: 69
										line: 4
									}
									start: Object {
										column: 14
										index: 49
										line: 3
									}
								}
								test: JSNumericLiteral {
									value: 2
									format: undefined
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 14
											index: 49
											line: 3
										}
										start: Object {
											column: 13
											index: 48
											line: 3
										}
									}
								}
								consequent: Array [
									JSBreakStatement {
										label: undefined
										loc: Object {
											filename: "input.js"
											end: Object {
												column: 18
												index: 69
												line: 4
											}
											start: Object {
												column: 12
												index: 63
												line: 4
											}
										}
									}
								]
							}
							JSSwitchCase {
								trailingComments: Array ["0"]
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 18
										index: 104
										line: 6
									}
									start: Object {
										column: 14
										index: 84
										line: 5
									}
								}
								test: JSNumericLiteral {
									value: 1
									format: undefined
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 14
											index: 84
											line: 5
										}
										start: Object {
											column: 13
											index: 83
											line: 5
										}
									}
								}
								consequent: Array [
									JSBreakStatement {
										label: undefined
										trailingComments: undefined
										loc: Object {
											filename: "input.js"
											end: Object {
												column: 18
												index: 104
												line: 6
											}
											start: Object {
												column: 12
												index: 98
												line: 6
											}
										}
									}
								]
							}
						]
					}
				]
			}
		}
	]
}
```
