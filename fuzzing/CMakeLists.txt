include(fuzz_helpers)

add_custom_target(build_fuzzers)

# Add fuzz targets
add_fuzzer(bliss)
add_fuzzer(edge_connectivity)
add_fuzzer(read_dimacs_flow)
add_fuzzer(read_dl)
add_fuzzer(read_edgelist)
add_fuzzer(read_gml)
add_fuzzer(read_graphdb)
add_fuzzer(read_graphml)
add_fuzzer(read_lgl)
add_fuzzer(read_ncol)
add_fuzzer(read_pajek)
add_fuzzer(vertex_connectivity)
add_fuzzer(vertex_separators)
