Meu nome é Pedro Barros Agostini do lab 7 e este é meu trabalho do Exame, um API capaz de criar, visualizar, editar e excluir tarefas

Colocarei um vídeo em anexo da atividade porque a entrada P2 do meu fone quebrou e eu não consigo usar meu microfone

Minhas rotas:

Route::get('/tasks', [TaskController::class, 'index']);
Route::post('/tasks', [TaskController::class, 'store']);
Route::get('/tasks/{task}', [TaskController::class, 'show']);
Route::put('/tasks/{task}', [TaskController::class, 'update']);
Route::delete('/tasks/{task}', [TaskController::class, 'destroy']);

OBS: Descobri o que tinha dado de errado no meu tabalho anterior, durante a instalação do laravel tinham alguns arquivos que não estavam sendo instalados tive que instalar o 7zip pra resolver
