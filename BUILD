genrule(
    name = "temp",
    outs = ["temp.txt"],
    cmd = """
    touch $@
    """,
    exec_properties = {
        # "workload-isolation-type": "firecracker",
    },
)
