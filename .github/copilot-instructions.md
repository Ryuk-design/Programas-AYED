# AI Coding Instructions for Programas-AYED

## Project Overview
This is a university-level Algorithms and Data Structures (AYED) educational repository for implementing and studying classic algorithms. Files are organized as standalone implementations of individual algorithms, typically one Python file per algorithm.

## Code Style & Patterns

### Algorithm Implementation Format
- **File naming**: `algorithm_name.py` (lowercase with underscores)
- **Function signature**: Core algorithm as the main function with minimal parameters (e.g., `insertion_sort(A)`)
- **Implementation approach**: Focus on clarity and educational value over optimization
- **Return value**: Typically returns the modified data structure or result directly

### Example Pattern: Sorting Algorithms
See [Insertion_sort.py](Insertion_sort.py) - demonstrates the standard format:
- Takes a list/array as primary parameter
- Modifies in-place and returns the result
- Clear variable names (`key`, `j`, `i`) aligned with algorithm pseudocode
- Readable logic without premature optimization

## Development Practices

### Testing & Validation
- Test implementations against basic cases: empty lists, single elements, sorted/reverse sorted arrays
- No automated test framework currently in use; manual validation is the practice
- Document edge cases that are tested

### Documentation
- Update [README.md](README.md) when adding new algorithm files
- Use the "Programitas a lo largo del semestre :)" format - include new filename and brief description
- No inline docstrings required but welcome for complex algorithms

## When Adding New Algorithms
1. Create `new_algorithm_name.py` in the root directory
2. Implement the core algorithm function with standard naming conventions
3. Return or modify the input appropriately for the algorithm type
4. Test with at least 3 different input cases
5. Update README.md with the new addition

## Project Scope
This repository captures **learning implementations** of algorithms taught in the AYED course. Focus on:
- Educational clarity
- Correctness of the algorithm logic
- Demonstrating understanding of the underlying concepts
- Standard algorithm structure and naming from course materials

Avoid:
- Complex optimizations that obscure the core algorithm
- External dependencies beyond Python standard library
- Multiple algorithm variants in a single file
