import 'package:flutter/material.dart';
import 'package:flutter/services.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      title: "Tela de Empréstimos",
      theme: ThemeData(
        primaryColor: Colors.blue,
      ),
      home: WidgetsBasicos(),
    );
  }
}

class WidgetsBasicos extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
        appBar: AppBar(
          leading: IconButton(onPressed: () {}, icon: Icon(Icons.arrow_back)),
          title: Container(
            padding: EdgeInsets.all(10),
            width: 2000,
            height: 60,
            child: TextField(
              decoration: InputDecoration(
                filled: true,
                fillColor: Colors.white,
                hintStyle: TextStyle(color: Colors.grey),
                border:
                    OutlineInputBorder(borderRadius: BorderRadius.circular(25)),
                hintText: 'Busque um usuário aqui.',
                prefixIcon: Icon(Icons.search),
                iconColor: Colors.grey.shade400,
              ),
            ),
          ),
        ),
        bottomNavigationBar: BottomNavigationBar(
          type: BottomNavigationBarType.fixed,
          items: const [
            BottomNavigationBarItem(
                icon: Icon(Icons.home), label: "Página Inicial"),
            BottomNavigationBarItem(icon: Icon(Icons.store), label: "Estoque"),
            BottomNavigationBarItem(
                icon: Icon(Icons.groups_2), label: "Usuários"),
            BottomNavigationBarItem(
                icon: Icon(Icons.account_box), label: "Minha Conta"),
          ],
          backgroundColor: Colors.blue,
          selectedItemColor: Colors.white,
          unselectedItemColor: Colors.grey.shade400,
        ),
        body: Container(
            height: double.infinity,
            child: Column(children: [
              Expanded(
                  child: ListView(
                      // crossAxisAlignment: CrossAxisAlignment.start,
                      children: [
                    Container(
                      decoration: BoxDecoration(
                        color: Colors.grey.shade200,
                        boxShadow: [
                          BoxShadow(
                            color: Colors.grey.shade400,
                            blurRadius: 1.0, // soften the shadow
                            spreadRadius: 0.5, //extend the shadow
                            offset: Offset(
                              0.0, // Move to right 5  horizontally
                              5.0, // Move to bottom 5 Vertically
                            ),
                          )
                        ],
                      ),
                      margin: const EdgeInsets.symmetric(
                          vertical: 16, horizontal: 10),
                      padding: const EdgeInsets.all(12),
                      child: Column(
                        crossAxisAlignment: CrossAxisAlignment.start,
                        children: [
                          Row(
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: [
                              const Text('Empréstimo 1',
                                  style:
                                      TextStyle(fontWeight: FontWeight.bold)),
                              IconButton(
                                  color: Colors.blue,
                                  onPressed: () async {},
                                  icon: const Icon(Icons.playlist_add)),
                            ],
                          ),
                          Column(
                            crossAxisAlignment: CrossAxisAlignment.start,
                            children: const [
                              Text('Matrícula: JA6012'),
                              Text('Data de saída: 15/01/2022'),
                              Text('E-mail: brunabrecailo@malwee.com.br')
                            ],
                          ),
                        ],
                      ),
                    ),
                    Container(
                      decoration: BoxDecoration(
                        color: Colors.grey.shade200,
                        boxShadow: [
                          BoxShadow(
                            color: Colors.grey.shade400,
                            blurRadius: 1.0, // soften the shadow
                            spreadRadius: 0.5, //extend the shadow
                            offset: Offset(
                              0.0, // Move to right 5  horizontally
                              5.0, // Move to bottom 5 Vertically
                            ),
                          )
                        ],
                      ),
                      margin: const EdgeInsets.symmetric(
                          vertical: 16, horizontal: 10),
                      padding: const EdgeInsets.all(12),
                      child: Column(
                        crossAxisAlignment: CrossAxisAlignment.start,
                        children: [
                          Row(
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: [
                              const Text('Empréstimo 2',
                                  style:
                                      TextStyle(fontWeight: FontWeight.bold)),
                              IconButton(
                                  color: Colors.blue,
                                  onPressed: () async {},
                                  icon: const Icon(Icons.playlist_add)),
                            ],
                          ),
                          Column(
                            crossAxisAlignment: CrossAxisAlignment.start,
                            children: const [
                              Text('Matrícula: JA3412'),
                              Text('Data de saída: 19/09/2021'),
                              Text('E-mail: edu_machado@malwee.com.br')
                            ],
                          ),
                        ],
                      ),
                    ),
                    Container(
                      decoration: BoxDecoration(
                        color: Colors.grey.shade200,
                        boxShadow: [
                          BoxShadow(
                            color: Colors.grey.shade400,
                            blurRadius: 1.0, // soften the shadow
                            spreadRadius: 0.5, //extend the shadow
                            offset: Offset(
                              0.0, // Move to right 5  horizontally
                              5.0, // Move to bottom 5 Vertically
                            ),
                          )
                        ],
                      ),
                      margin: const EdgeInsets.symmetric(
                          vertical: 16, horizontal: 10),
                      padding: const EdgeInsets.all(12),
                      child: Column(
                        crossAxisAlignment: CrossAxisAlignment.start,
                        children: [
                          Row(
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: [
                              const Text('Empréstimo 3',
                                  style:
                                      TextStyle(fontWeight: FontWeight.bold)),
                              IconButton(
                                  color: Colors.blue,
                                  onPressed: () async {},
                                  icon: const Icon(Icons.playlist_add)),
                            ],
                          ),
                          Column(
                            crossAxisAlignment: CrossAxisAlignment.start,
                            children: const [
                              Text('Matrícula: JA3490'),
                              Text('Data de saída: 10/02/2022'),
                              Text('E-mail: brunabrecailo@malwee.com.br')
                            ],
                          ),
                        ],
                      ),
                    ),
                    Container(
                      decoration: BoxDecoration(
                        color: Colors.grey.shade200,
                        boxShadow: [
                          BoxShadow(
                            color: Colors.grey.shade400,
                            blurRadius: 1.0, // soften the shadow
                            spreadRadius: 0.5, //extend the shadow
                            offset: Offset(
                              0.0, // Move to right 5  horizontally
                              5.0, // Move to bottom 5 Vertically
                            ),
                          )
                        ],
                      ),
                      margin: const EdgeInsets.symmetric(
                          vertical: 16, horizontal: 10),
                      padding: const EdgeInsets.all(12),
                      child: Column(
                        crossAxisAlignment: CrossAxisAlignment.start,
                        children: [
                          Row(
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: [
                              const Text('Empréstimo 4',
                                  style:
                                      TextStyle(fontWeight: FontWeight.bold)),
                              IconButton(
                                  color: Colors.blue,
                                  onPressed: () async {},
                                  icon: const Icon(Icons.playlist_add)),
                            ],
                          ),
                          Column(
                            crossAxisAlignment: CrossAxisAlignment.start,
                            children: const [
                              Text('Matrícula: JA3490'),
                              Text('Data de saída: 19/02/2023'),
                              Text('E-mail: edu_machado@malwee.com.br')
                            ],
                          ),
                        ],
                      ),
                    ),
                    Container(
                      decoration: BoxDecoration(
                        color: Colors.grey.shade200,
                        boxShadow: [
                          BoxShadow(
                            color: Colors.grey.shade400,
                            blurRadius: 1.0, // soften the shadow
                            spreadRadius: 0.5, //extend the shadow
                            offset: Offset(
                              0.0, // Move to right 5  horizontally
                              5.0, // Move to bottom 5 Vertically
                            ),
                          )
                        ],
                      ),
                      margin: const EdgeInsets.symmetric(
                          vertical: 16, horizontal: 10),
                      padding: const EdgeInsets.all(12),
                      child: Column(
                        crossAxisAlignment: CrossAxisAlignment.start,
                        children: [
                          Row(
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: [
                              const Text('Empréstimo 5',
                                  style:
                                      TextStyle(fontWeight: FontWeight.bold)),
                              IconButton(
                                  color: Colors.blue,
                                  onPressed: () async {},
                                  icon: const Icon(Icons.playlist_add)),
                            ],
                          ),
                          Column(
                            crossAxisAlignment: CrossAxisAlignment.start,
                            children: const [
                              Text('Matrícula: JA3490'),
                              Text('Data de saída: 10/02/2022'),
                              Text('E-mail: brunabrecailo@malwee.com.br')
                            ],
                          ),
                        ],
                      ),
                    ),
                  ])),
            ])));
  }
}
