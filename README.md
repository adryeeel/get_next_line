# get_next_line

![C Language](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Ubuntu OS](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

This project, `get_next_line`, consists of implementing a function that performs stream processing, returning a line read from a file descriptor, including the standard input.

This project is a fundamental part of the curriculum at 42 school, designed to strengthen your understanding of buffer management, file manipulation, memory leaks and static variables in C.

## Project Overview

The `get_next_line` function behaviour is very simple:

- It receives a file descriptor as paramenter.

- The file descriptor is read to a buffer.

- The buffer is processed and the next line is returned. A line is limited by a `\n` char.

- For each sucessive call of `get_next_line`, the next line from `fd` is returned, without repetition.

- When there is nothing more to process, `NULL` is returned.

## Key Features

- Memory leak proof.

- Efficient parsing of input from any file descriptor.

- Handles multiple file descriptors simultaneously.

- Supports custom `BUFFER_SIZE` values through the `-D` compiler flag for optimal performance.

## Usage

- Clone the repository: `git clone https://github.com/adryeeel/get_next_line.git`.

- Enter the directory: `cd get_next_line`

- Include the `get_next_line.h` header file in your C projects.

- Compile your project along with the `get_next_line.c` and `get_next_line_utils.c` files.

## Evaluation

This project was assigned as a ⭐ outstanding project by three 42 school peers and has received the maximum evaluation score – **125%**, including a bonus of 25 points.

![Score 125%](README/evaluation-score.png)

## Feedback and Support

If you encounter any issues or have suggestions for improving the project, please open an issue on GitHub. I'm very glad to receive feedbacks on my projects!

## License

This project is licensed under the [MIT License](LICENSE).
