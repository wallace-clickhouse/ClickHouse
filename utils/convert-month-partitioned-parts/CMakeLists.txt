add_executable (convert-month-partitioned-parts main.cpp)
target_link_libraries(convert-month-partitioned-parts PRIVATE dbms clickhouse_parsers boost::program_options)
