cmake_minimum_required(VERSION 3.16)
project(alx_low_level_programming C)

set(CMAKE_C_STANDARD 11)
add_executable(
    delete_dnodeint
    4-delete_dnodeint/main.c
    4-delete_dnodeint/free_dlistint.c
    4-delete_dnodeint/print_dlistint.c
    4-delete_dnodeint/add_dnodeint_end.c
    4-delete_dnodeint/delete_dnodeint_at_index.c
)