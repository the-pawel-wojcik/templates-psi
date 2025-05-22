# Psi
How to use the [Psi](https://psicode.org/) program.

## Disk IO
Set `PSI_SCRATCH`. Defaults to `/tmp/`.

## Concurrency
- Set the number of threads as a command line argument
```bash
psi4 -i input.psi -o output.po -n 4
```
- Specify the number of threads in the input file
```python
thread_count = 4
set_num_threads(thread_count)
```

## Environmnet
`PSIPATH` path to external modules.

## Command Line Options
`-i` input file, defaults to `input.dat`.

`-o` output file, defaults to `output.dat`.

```bash
psi4 --help  # list all options
```

## Examples
[official](https://github.com/psi4/psi4/tree/master/samples)
