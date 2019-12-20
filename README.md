Use [Jupyter Notebook Python, Scala, R, Spark, Mesos Stack](https://github.com/jupyter/docker-stacks/tree/master/all-spark-notebook) to run the notebooks.

```sh
  # e.g., to bind only current folder.
  docker run -v $(pwd):/home/jovyan/work -p 8888:8888 --name jupyter jupyter/all-spark-notebook

  # e.g., too bind a project folder.
  docker run -v /Users/slee/p:/home/jovyan/p -p 8888:8888 --name jupyter jupyter/all-spark-notebook
```
