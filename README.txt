1. libraries required to run the project

python - 3.12.0
numpy - 1.26.2
opencv_python - 4.8.1.78

2. how to run each task and where to look for the output file.

In princiu, se ruleaza pe rand fiecare celula cu cod a fisierului .ipynb

Task 1 & Task 2:
function: 
 - get_careu(image), where input_folder_name is the path to the folder containing the images for task1
 - clasifica_cifra(patch, path), where path is the path to the folder containing the template images
 - determina_clasificatie_careu(thresh, line_horizontal, line_vertical), where line_horizontal and line_vertical are determined in two cells above
 - task1_and_task2(img_path, sol_path), where img_path is the path to the folder containing the images for the task and sol_path is the path to the folder containing the solution files

output: the output .txt files are in sol_path

Task 3: 
function:
 - get_pieces(image, sol_path), where sol_path is the path to the folder containing the solution files resulted from task 1 and 2 
 - get_points_piece_position(piece_poz) 
 - write_score(image, scor, sol_path), where ol_path is the path to the folder containing the solution files resulted from task 1 and 2 (where i want to append the scores)
 - get_game_score(game_number, img_path, sol_path), where img_path is the path to the folder containing the images for the task and sol_path is the path to the folder containing the solution files
 - must run the final cell containing a for iteration in which is called get_game_score function

output: the output .txt files are in sol_path
