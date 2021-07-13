python_library(
    name="mock_script_src",
    sources=["mock_script.py"],
)

pex_binary(
    name="mock_script",
    entry_point="mock_script.py",
    dependencies=[
        ":mock_script_src",
        "//src/python/a_lib"
    ],
)
