# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 147`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 18
      index: 18
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 18
          index: 18
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 18
            index: 18
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingObjectPattern {
              rest: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 12
                  index: 12
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
              properties: Array [
                BindingObjectPatternProperty {
                  key: ComputedPropertyKey {
                    value: ReferenceIdentifier {
                      name: 'x'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'x'
                        end: Object {
                          column: 7
                          index: 7
                          line: 1
                        }
                        start: Object {
                          column: 6
                          index: 6
                          line: 1
                        }
                      }
                    }
                    variance: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 8
                        index: 8
                        line: 1
                      }
                      start: Object {
                        column: 5
                        index: 5
                        line: 1
                      }
                    }
                  }
                  value: BindingIdentifier {
                    name: 'y'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'y'
                      end: Object {
                        column: 11
                        index: 11
                        line: 1
                      }
                      start: Object {
                        column: 10
                        index: 10
                        line: 1
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 11
                      index: 11
                      line: 1
                    }
                    start: Object {
                      column: 5
                      index: 5
                      line: 1
                    }
                  }
                }
              ]
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 18
                index: 18
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: ObjectExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 18
                  index: 18
                  line: 1
                }
                start: Object {
                  column: 15
                  index: 15
                  line: 1
                }
              }
              properties: Array [
                ObjectProperty {
                  key: StaticPropertyKey {
                    value: Identifier {
                      name: 'y'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'y'
                        end: Object {
                          column: 17
                          index: 17
                          line: 1
                        }
                        start: Object {
                          column: 16
                          index: 16
                          line: 1
                        }
                      }
                    }
                    variance: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 17
                        index: 17
                        line: 1
                      }
                      start: Object {
                        column: 16
                        index: 16
                        line: 1
                      }
                    }
                  }
                  value: ReferenceIdentifier {
                    name: 'y'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'y'
                      end: Object {
                        column: 17
                        index: 17
                        line: 1
                      }
                      start: Object {
                        column: 16
                        index: 16
                        line: 1
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 17
                      index: 17
                      line: 1
                    }
                    start: Object {
                      column: 16
                      index: 16
                      line: 1
                    }
                  }
                }
              ]
            }
          }
        ]
      }
    }
  ]
}
```
