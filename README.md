# ecran

namespace App\Controller;
use App\Entity\Post; 
use Symfony\Bundle\FrameworkBundle\Controller\AbstractController;
use Symfony\Component\Routing\Annotation\Route;
class DefaultController extends AbstractController { /** * @Route("/", name="homepage") */ public function index() 
