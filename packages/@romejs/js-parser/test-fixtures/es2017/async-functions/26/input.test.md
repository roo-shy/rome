# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > 26`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 36
      index: 36
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 36
          index: 36
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: CallExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 36
            index: 36
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        callee: ReferenceIdentifier {
          name: 'f'
          loc: Object {
            filename: 'input.js'
            identifierName: 'f'
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
          ReferenceIdentifier {
            name: 'a'
            loc: Object {
              filename: 'input.js'
              identifierName: 'a'
              end: Object {
                column: 3
                index: 3
                line: 1
              }
              start: Object {
                column: 2
                index: 2
                line: 1
              }
            }
          }
          ArrowFunctionExpression {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 32
                index: 32
                line: 1
              }
              start: Object {
                column: 5
                index: 5
                line: 1
              }
            }
            head: FunctionHead {
              async: true
              hasHoistedVars: false
              rest: undefined
              returnType: undefined
              thisType: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 19
                  index: 19
                  line: 1
                }
                start: Object {
                  column: 5
                  index: 5
                  line: 1
                }
              }
              params: Array [
                BindingIdentifier {
                  name: 'x'
                  loc: Object {
                    filename: 'input.js'
                    identifierName: 'x'
                    end: Object {
                      column: 12
                      index: 12
                      line: 1
                    }
                    start: Object {
                      column: 11
                      index: 11
                      line: 1
                    }
                  }
                }
                BindingIdentifier {
                  name: 'y'
                  loc: Object {
                    filename: 'input.js'
                    identifierName: 'y'
                    end: Object {
                      column: 15
                      index: 15
                      line: 1
                    }
                    start: Object {
                      column: 14
                      index: 14
                      line: 1
                    }
                  }
                }
              ]
            }
            body: AwaitExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 32
                  index: 32
                  line: 1
                }
                start: Object {
                  column: 20
                  index: 20
                  line: 1
                }
              }
              argument: ArrayExpression {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 32
                    index: 32
                    line: 1
                  }
                  start: Object {
                    column: 26
                    index: 26
                    line: 1
                  }
                }
                elements: Array [
                  ReferenceIdentifier {
                    name: 'x'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'x'
                      end: Object {
                        column: 28
                        index: 28
                        line: 1
                      }
                      start: Object {
                        column: 27
                        index: 27
                        line: 1
                      }
                    }
                  }
                  ReferenceIdentifier {
                    name: 'y'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'y'
                      end: Object {
                        column: 31
                        index: 31
                        line: 1
                      }
                      start: Object {
                        column: 30
                        index: 30
                        line: 1
                      }
                    }
                  }
                ]
              }
            }
          }
          ReferenceIdentifier {
            name: 'b'
            loc: Object {
              filename: 'input.js'
              identifierName: 'b'
              end: Object {
                column: 35
                index: 35
                line: 1
              }
              start: Object {
                column: 34
                index: 34
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
}
```
