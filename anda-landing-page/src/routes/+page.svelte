<main class="flex flex-col h-screen bg-slate-200">
    <nav class="flex justify-center border border-b-2 text-2xl font-bold">
        <ul class="flex flex-row space-x-96">
            <li href="#" class="p-4 px-8 hover:bg-sky-500 active:bg-sky-700 hover:cursor-pointer hover:text-slate-100 duration-150">Download</li>
            <li href="#" class="p-4 px-8 hover:bg-sky-500 active:bg-sky-700 hover:cursor-pointer hover:text-slate-100 duration-150">About</li>
            <li href="#" class="p-4 px-8 hover:bg-sky-500 active:bg-sky-700 hover:cursor-pointer hover:text-slate-100 duration-150">Citation</li>
        </ul>
    </nav>
    <Download/>
</main>

<script>
import Download from './components/Download.svelte'
</script>
