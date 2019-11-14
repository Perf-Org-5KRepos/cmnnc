# cmdnn

Documentation can be found in:
git@github.ibm.com:computational-memory-stack/cmdnn-docs.git

## Dependencies

We use `virtualenv` for installing python dependencies:

```
$ virtualenv -p python3 cmenv
$ source cmenv/bin/activate
$ pip install islpy astor onnxruntime numpy onnx pytest
```

Note: you might have to install `libpython3.x-dev` or the equivalent package to
for islpy installation to work.
