genrule(
    name = "temp",
    outs = [
        "1.txt",
        "2.txt",
    ],
    cmd = """
    touch $(execpath 1.txt)
    exit 0
    """,
    exec_properties = {
        # "workload-isolation-type": "firecracker",
    },
)
