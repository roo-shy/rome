# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > interface > method-plain`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 66
      line: 5
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    TSInterfaceDeclaration {
      id: BindingIdentifier {
        name: 'I'
        loc: Object {
          filename: 'input.ts'
          identifierName: 'I'
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
      extends: undefined
      typeParameters: undefined
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 1
          index: 65
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: TSInterfaceBody {
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 1
            index: 65
            line: 4
          }
          start: Object {
            column: 12
            index: 12
            line: 1
          }
        }
        body: Array [
          TSMethodSignature {
            key: StaticPropertyKey {
              value: Identifier {
                name: 'm'
                loc: Object {
                  filename: 'input.ts'
                  identifierName: 'm'
                  end: Object {
                    column: 5
                    index: 19
                    line: 2
                  }
                  start: Object {
                    column: 4
                    index: 18
                    line: 2
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 5
                  index: 19
                  line: 2
                }
                start: Object {
                  column: 4
                  index: 18
                  line: 2
                }
              }
            }
            optional: false
            returnType: undefined
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 8
                index: 22
                line: 2
              }
              start: Object {
                column: 4
                index: 18
                line: 2
              }
            }
            meta: TSSignatureDeclarationMeta {
              parameters: Array []
              rest: undefined
              typeParameters: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 7
                  index: 21
                  line: 2
                }
                start: Object {
                  column: 5
                  index: 19
                  line: 2
                }
              }
            }
          }
          TSMethodSignature {
            key: StaticPropertyKey {
              value: Identifier {
                name: 'm'
                loc: Object {
                  filename: 'input.ts'
                  identifierName: 'm'
                  end: Object {
                    column: 5
                    index: 28
                    line: 3
                  }
                  start: Object {
                    column: 4
                    index: 27
                    line: 3
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 5
                  index: 28
                  line: 3
                }
                start: Object {
                  column: 4
                  index: 27
                  line: 3
                }
              }
            }
            optional: false
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 40
                index: 63
                line: 3
              }
              start: Object {
                column: 4
                index: 27
                line: 3
              }
            }
            returnType: VoidKeywordTypeAnnotation {
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 39
                  index: 62
                  line: 3
                }
                start: Object {
                  column: 35
                  index: 58
                  line: 3
                }
              }
            }
            meta: TSSignatureDeclarationMeta {
              typeParameters: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 39
                  index: 62
                  line: 3
                }
                start: Object {
                  column: 5
                  index: 28
                  line: 3
                }
              }
              parameters: Array [
                BindingIdentifier {
                  name: 'x'
                  loc: Object {
                    filename: 'input.ts'
                    identifierName: 'x'
                    end: Object {
                      column: 7
                      index: 30
                      line: 3
                    }
                    start: Object {
                      column: 6
                      index: 29
                      line: 3
                    }
                  }
                  meta: PatternMeta {
                    optional: true
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 16
                        index: 39
                        line: 3
                      }
                      start: Object {
                        column: 6
                        index: 29
                        line: 3
                      }
                    }
                    typeAnnotation: NumberKeywordTypeAnnotation {
                      loc: Object {
                        filename: 'input.ts'
                        end: Object {
                          column: 16
                          index: 39
                          line: 3
                        }
                        start: Object {
                          column: 10
                          index: 33
                          line: 3
                        }
                      }
                    }
                  }
                }
              ]
              rest: BindingIdentifier {
                name: 'y'
                loc: Object {
                  filename: 'input.ts'
                  identifierName: 'y'
                  end: Object {
                    column: 22
                    index: 45
                    line: 3
                  }
                  start: Object {
                    column: 21
                    index: 44
                    line: 3
                  }
                }
                meta: PatternMeta {
                  optional: undefined
                  loc: Object {
                    filename: 'input.ts'
                    end: Object {
                      column: 32
                      index: 55
                      line: 3
                    }
                    start: Object {
                      column: 21
                      index: 44
                      line: 3
                    }
                  }
                  typeAnnotation: TSArrayType {
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 32
                        index: 55
                        line: 3
                      }
                      start: Object {
                        column: 24
                        index: 47
                        line: 3
                      }
                    }
                    elementType: NumberKeywordTypeAnnotation {
                      loc: Object {
                        filename: 'input.ts'
                        end: Object {
                          column: 30
                          index: 53
                          line: 3
                        }
                        start: Object {
                          column: 24
                          index: 47
                          line: 3
                        }
                      }
                    }
                  }
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
