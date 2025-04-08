# New_order_site
import Image from 'next/image';

export default function Home() {
  return (
    <main className="p-6 max-w-7xl mx-auto space-y-16">
      {/* Título Principal */}
      <section className="text-center">
        <h1 className="text-4xl font-bold text-yellow-400 drop-shadow-lg">New Order / Clash of ON</h1>
        <p className="text-lg mt-2 text-gray-200">A comunidade unida dos verdadeiros guerreiros do Clash of Clans</p>
      </section>

      {/* Galeria de Conquistas */}
      <section>
        <h2 className="text-2xl font-semibold mb-4 text-white">Conquistas Recentes</h2>
        <div className="grid grid-cols-1 sm:grid-cols-3 gap-4">
          <Image src="/images/conquista1.jpg" alt="Conquista 1" width={300} height={200} className="rounded-xl shadow-lg" />
          <Image src="/images/conquista2.jpg" alt="Conquista 2" width={300} height={200} className="rounded-xl shadow-lg" />
          <Image src="/images/conquista3.jpg" alt="Conquista 3" width={300} height={200} className="rounded-xl shadow-lg" />
        </div>
      </section>

      {/* Depoimentos da Comunidade */}
      <section>
        <h2 className="text-2xl font-semibold mb-4 text-white">Depoimentos</h2>
        <div className="space-y-4">
          <blockquote className="bg-gray-800 p-4 rounded-lg border-l-4 border-yellow-400 text-white">
            "Melhor clã que já participei, a união aqui é tudo!"
          </blockquote>
          <blockquote className="bg-gray-800 p-4 rounded-lg border-l-4 border-yellow-400 text-white">
            "Aqui ninguém fica pra trás. A guerra é séria, mas a resenha também!"
          </blockquote>
        </div>
      </section>

      {/* Próximos Eventos */}
      <section>
        <h2 className="text-2xl font-semibold mb-4 text-white">Próximos Eventos</h2>
        <ul className="list-disc list-inside text-white space-y-2">
          <li>Campeonato Interno – 20 de Abril</li>
          <li>Recrutamento ao vivo no Discord – 25 de Abril</li>
          <li>Batalha dos Líderes – 30 de Abril</li>
        </ul>
      </section>

      {/* Ranking Interno */}
      <section>
        <h2 className="text-2xl font-semibold mb-4 text-white">Ranking Interno</h2>
        <ol className="text-white list-decimal list-inside space-y-1">
          <li>LíderMaster – 10.000 troféus</li>
          <li>WarriorPro – 9.200 troféus</li>
          <li>DragãoElite – 8.700 troféus</li>
        </ol>
      </section>

      {/* Mural de Avisos */}
      <section>
        <h2 className="text-2xl font-semibold mb-4 text-white">Mural de Avisos</h2>
        <div className="bg-yellow-100 text-yellow-900 p-4 rounded-md shadow-md">
          <strong>Aviso importante:</strong> Não esqueça de fazer seus ataques na guerra até as 22h!
        </div>
      </section>
    </main>
  );
}
